# https://starkware.co/stark-101/

STARK 101 is a hands-on tutorial on how to write a STARK prover from scratch (in Python).

Each section has a short explainer video and a Jupyter practice Notebook. To use the Notebook, you can either install it locally via our GitHub repository, or run it online via Binder.

The tutorial assumes familiarity with Python and some mathematical background  (including finite field arithmetics).

STARK 101 was originally a live workshop, held in Tel Aviv in September 2019 as part of StarkWare Sessions.

To run the tutorial online via Binder Start Here

Part I: Statement, LDE & Commitment
Introducing the statement we will be proving and the concepts of Low Degree Extension (LDE) and commitment using Merkle tree.

Part II: Polynomial Constraints
Create a set of polynomial constraints, reduce the original statement to a new one, create a composition polynomial and commit on it.

Part III: FRI Commitment
Dive into the FRI protocol and use it to prove that a polynomial is close to one of a bounded degree.

Part IV: The Proof
We tie it all together to build an end-to-end proof.

