

Benchmark1 is a static frontal solution of a thermal model with ~100,000 DOF. This primarily stresses the machines hard drive.
Benchmark5 is a small contact with plasticity model which will primarily exercise the machines CPU.
Both codes have been calculated with Ansys 16.1 utilising 1 node and 1 core with a single thread per process using 24GB of real memory and run from /data.

The parameters and switches used with these benchmarks can be viewed in the Bench*.SubmissionParams.txt file found in the primary directories for each HPC.
The Ansys generated output.out is an interesting file and the end-of-file data reveals solver calculation data in more detail.
In each case the bench0*.inp file has been processed.
