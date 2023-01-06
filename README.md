### About
We have reproduced the results for the number of quantum gates required for Hamiltonian simulation of single single Trotter step in SrVO<sub>3</sub>, as estimated in the following paper.
We hope that you cite the paper when you use our data.

- S. Kanno, S. Endo, T. Utsumi, and T. Tada, Resource Estimations for the Hamiltonian Simulation in Correlated Electron Materials, [Phys. Rev. A 106, 012612 (2022)](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.106.012612).

The input data of the ab initio calculations by [Quantum ESPRESSO](https://www.quantum-espresso.org) is in QE directrory.
The input and output data of the ab initio downfolding by [RESPACK](https://sites.google.com/view/kazuma7k6r) is in RESPACK directrory.
The results of the gate count estimation with the number of unit cells $N_{cells}=100$ are in Estimation directrory. The counts in the paper were almost reproduced.
All calculations were performed on the Mitsubishi Chemical Corporation (MCC) high-performance computer (HPC) system “NAYUTA”, where “NAYUTA” is a nickname for MCC HPC and is not a product or service name of MCC.

### Folder structures
- LICENSE
- README.md
- QE
  - band.in, nscf.in, scf.in 
- RESPACK
  - respack.in
  - dir-model
    - zvo_bandkpts.dat, zvo_dr.dat, zvo_ef.dat, zvo_geom.dat, zvo_geom.xsf, zvo_hr.dat, zvo_jr.dat, zvo_mkkpts.dat, zvo_ur.dat
- Estimation
  - SrVO3.csv