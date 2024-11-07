# [NVIDIA DLI - Advanced Technical Workshop: Fundamentals of Accelerated Computing with CUDA Python](https://learn.nvidia.com/courses/course-detail?course_id=course-v1:DLI+C-AC-02+V1) - COMPLETED!

# Fundamentals of Accelerated Computing with CUDA Python

This repository and course provide an in-depth introduction to the **Fundamentals of Accelerated Computing with CUDA Python**, offered by NVIDIA's Deep Learning Institute (DLI). The course is designed to teach developers and researchers how to accelerate Python applications using GPU parallelism through CUDA Python, leveraging the power of NVIDIA GPUs.

## Learning Objectives:
- Understand the fundamentals of GPU architecture and how it differs from CPU-based computing.
- Learn to write and optimize parallel code using CUDA Python and Numba.
- Implement custom CUDA kernels in Python for maximum flexibility and performance.
- Manage memory transfers between CPU and GPU efficiently.
- Utilize advanced techniques like memory coalescing and shared memory for performance optimization.

## Overview of CUDA Python:
CUDA Python is a framework that allows developers to harness the computational power of NVIDIA GPUs directly from Python. It integrates with popular libraries such as Numba, enabling users to write GPU-accelerated code with minimal changes to their existing Python workflows.

## Key Components of the Course:

### 1. Introduction to CUDA Programming:
The course begins by covering the basics of NVIDIA GPU architecture and how CUDA enables parallel computing. Participants will learn:
- How GPUs are structured for massive parallelism.
- The difference between CPU and GPU execution models.

### 2. Introduction to CUDA Python with Numba:
Numba is a just-in-time compiler that translates a subset of Python and NumPy code into fast machine code, enabling GPU acceleration. Key topics include:
- Using Numba decorators to accelerate numerical functions.
- Optimizing memory transfers between host (CPU) and device (GPU).

### 3. Custom CUDA Kernels in Python:
Participants will learn how to write custom CUDA kernels directly in Python using Numba, allowing for more control over parallel execution. Topics covered:
- Understanding the CUDA thread hierarchy (grids, blocks, threads).
- Launching massively parallel kernels on the GPU.
- Avoiding race conditions with atomic operations.

### 4. Memory Management and Optimization:
Efficient memory management is crucial for maximizing performance in GPU applications. This section covers:
- Techniques for optimizing memory bandwidth using memory coalescing.
- Using on-device shared memory to minimize data transfer overhead.

### 5. Performance Tuning Techniques:
The course provides strategies for tuning performance, including:
- Profiling GPU applications to identify bottlenecks.
- Optimizing kernel execution by adjusting thread block sizes and grid dimensions.

## Key Libraries and Tools:

### Numba:
Numba is a key tool used throughout the course. It allows developers to:
- Accelerate NumPy ufuncs (universal functions) with minimal code changes.
- Write custom CUDA kernels for specific tasks that require high flexibility.

### CUDA Toolkit:
Participants will work with the CUDA Toolkit, which provides essential tools such as:
- The CUDA runtime API for managing GPU resources.
- Profiling tools like `nvprof` for performance analysis.

## Best Practices for Refactoring CPU Workflows:
The course emphasizes best practices for refactoring existing CPU-based workflows into GPU-based ones:
- Identify computational bottlenecks where GPUs can provide significant speedups.
- Use Numba’s decorators to accelerate existing NumPy code without rewriting entire applications.
- Accelerating linear algebra operations originally designed for CPUs.
- Implementing Monte Carlo simulations using random number generation on GPUs.

## Comparison Between CPU vs. GPU Workflows:

| Aspect                   | CPU Workflow (Traditional)                      | GPU Workflow (CUDA Python)                              |
|--------------------------|-------------------------------------------------|---------------------------------------------------------|
| Data Processing Time      | Slower due to sequential execution              | Faster due to parallel processing on GPUs                |
| Algorithm Execution Time  | Longer due to limited CPU cores                 | Shorter due to massive parallelism on GPUs               |
| Scalability               | Limited by CPU resources                        | Scalable across multiple GPUs                            |
| API Familiarity           | NumPy/Python                                    | Similar APIs via Numba/NumPy                             |

## Conclusion:
By completing this course, participants will gain hands-on experience in building high-performance applications using NVIDIA's CUDA Python framework. They will be equipped with the skills necessary to:

- Refactor existing CPU-based applications into faster, GPU-based ones.
- Write new custom kernels for advanced parallel processing tasks.

This course is ideal for developers who have basic Python knowledge but want to explore how GPU acceleration can significantly improve the performance of their applications.

## Instructor-Led Workshop Outline:

<p style="text-align:center">
    <a href="https://learn.nvidia.com/courses/course-detail?course_id=course-v1:DLI+C-AC-02+V1" target="_blank">
    <img src="nvidia_cuda_portfolio/images/Workshop_Outline_FAC_CUDA_Python.png" alt="NVIDIA-DLI-Fundamentals of Accelerated Computing with CUDA Python"  />
    </a>
</p>

## [Certificate Of Competency:](https://learn.nvidia.com/certificates?id=bbfe2cfa7cee4ec995553febfcd1a033)

<p style="text-align:center">
    <a href="https://learn.nvidia.com/certificates?id=bbfe2cfa7cee4ec995553febfcd1a033" target="_blank">
    <img src="nvidia_cuda_portfolio/images/CC_FAC_CUDA_Python.png" alt="NVIDIA-DLI-Fundamentals of Accelerated Computing with CUDA Python"  />
    </a>
</p>
