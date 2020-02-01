# OpenMP-to-parallelize-the-deqn-code

# deqn - a simple 2D heat diffusion simulation

`deqn` is a program that solves the 2D diffusion equation on a structured mesh.
Three different schemes are provided:

1. A simple explicit update scheme,
2. An iterative (matrix-free) Jacobi scheme, and
3. A scheme that uses the HYPRE library to solve the system of linear equations.

## Building

- To build the first two schemes, just type `make`.
- To build `deqn` with HYPRE, set the variable `HYPRE_DIR` in the Makefile, and
  ensure that the `CXXFLAGS` variable defines `HAVE_HYPRE`.

## Running

Using your favourite MPI flavour:

    mpirun -n 4 ./deqn <input-file>

## Input Files

The file `test/square.in` demonstrates the supported input parameters, most importantly:

- `scheme <scheme>` can be used to select which scheme to use (`explicit`, `jacobi`, or `hypre`).
- `vis_frequency <n>` controls how often visualisation files are written out.
- `subregion <xmin> <ymin> <xmax> <ymax>` specifies the region of the problem domain that will be initially heated.


# 加微信 qiushiwenmeng

# [代做各类CS相关课程和程序语言](https://powcoder.com/)

[成功案例](https://powcoder.com/tag/成功案例/)

[java代写](https://powcoder.com/tag/java/) [c/c++代写](https://powcoder.com/tag/c/) [python代写](https://powcoder.com/tag/python/) [drracket代写](https://powcoder.com/tag/drracket/) [MIPS汇编代写](https://powcoder.com/tag/MIPS/) [matlab代写](https://powcoder.com/tag/matlab/) [R语言代写](https://powcoder.com/tag/r/) [javascript代写](https://powcoder.com/tag/javascript/)

[prolog代写](https://powcoder.com/tag/prolog/) [haskell代写](https://powcoder.com/tag/haskell/) [processing代写](https://powcoder.com/tag/processing/) [ruby代写](https://powcoder.com/tag/ruby/) [scheme代写](https://powcoder.com/tag/drracket/) [ocaml代写](https://powcoder.com/tag/ocaml/) [lisp代写](https://powcoder.com/tag/lisp/)

- [数据结构算法 data structure algorithm 代写](https://powcoder.com/category/data-structure-algorithm/)
- [计算机网络 套接字编程 computer network socket programming 代写](https://powcoder.com/category/network-socket/)
- [数据库 DB Database SQL 代写](https://powcoder.com/category/database-db-sql/)
- [机器学习 machine learning 代写](https://powcoder.com/category/machine-learning/)
- [编译器原理 Compiler 代写](https://powcoder.com/category/compiler/)
- [操作系统OS(Operating System) 代写](https://powcoder.com/category/操作系统osoperating-system/)
- [计算机图形学 Computer Graphics opengl webgl 代写](https://powcoder.com/category/computer-graphics-opengl-webgl/)
- [人工智能 AI Artificial Intelligence 代写](https://powcoder.com/category/人工智能-ai-artificial-intelligence/)
- [大数据 Hadoop Map Reduce Spark HBase 代写](https://powcoder.com/category/hadoop-map-reduce-spark-hbase/)
- [系统编程 System programming 代写](https://powcoder.com/category/sys-programming/)
- [网页应用 Web Application 代写](https://powcoder.com/category/web/)
- [自然语言处理 NLP natural language processing 代写](https://powcoder.com/category/nlp/)
- [计算机体系结构 Computer Architecture 代写](https://powcoder.com/category/computer-architecture/)
- [计算机安全密码学computer security cryptography 代写](https://powcoder.com/category/computer-security/)
- [计算机理论 Computation Theory 代写](https://powcoder.com/category/computation-theory/)
- [计算机视觉(Compute Vision) 代写](https://powcoder.com/category/计算机视觉compute-vision/)


