---
layout: page
title: Sorting-Visualizer
description: A visualization of different sorting algorithms.
img: assets/img/sorting_visualizer.png
importance: 2
category: fun
---

## [Try Out Here](https://adrianoweid.github.io/sorting-visualizer/)

As someone with a keen interest in algorithms, I created this tool to visually demonstrate how different sorting algorithms work.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="/assets/img/sorting_visualizer/sorting_visualizer_screenshot.png" title="Sorting Visualizer Interface" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This is the main interface of the Sorting Visualizer, showcasing various algorithms at work.
</div>

## Algorithm Descriptions and Complexities

Here's a brief overview of each sorting algorithm included in the Sorting Visualizer, along with their time complexities:

### Bubble Sort
**Time Complexity:** Average and worst - \(O(n^2)\), Best - \(O(n)\) when the array is already nearly sorted.
Bubble Sort is a simple algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. This process is repeated until the list is sorted. It is particularly inefficient on large lists due to its \(O(n^2)\) complexity, but it has a notable advantage: it detects whether the list is already sorted.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="/assets/img/sorting_visualizer/bubblesort_screenshot.webp" title="Bubble Sort" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Bubble Sort
</div>

### Merge Sort
**Time Complexity:** Always \(O(n \log n)\).
Merge Sort is a divide-and-conquer algorithm that splits the list into halves, recursively sorts each half, and then merges them back into a complete sorted list. This method is particularly efficient on large lists and performs consistently well regardless of the initial order of elements.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="/assets/img/sorting_visualizer/mergesort_screenshot.png" title="Merge Sort" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Merge Sort
</div>

### Quick Sort
**Time Complexity:** Average - \(O(n \log n)\), Worst - \(O(n^2)\), though the worst case is rare.
Quicksort is highly efficient and works by selecting a 'pivot' element from the array and partitioning the other elements into two sub-arrays, according to whether they are less than or greater than the pivot. The sub-arrays are then sorted recursively. The choice of pivot and strategy for partitioning can affect the performance significantly.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="/assets/img/sorting_visualizer/quicksort_screenshot.png" title="Quick Sort" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Quick Sort
</div>

### Heap Sort
**Time Complexity:** Always \(O(n \log n)\).
Heapsort involves building a heap from the data, then repeatedly removing the largest element from the heap and adding it to the end of the sorted list. This method combines the advantages of the best sorting techniques with space efficiency since it requires only a constant amount \(O(1)\) of additional memory.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="/assets/img/sorting_visualizer/heapsort_screenshot.png" title="Heap Sort" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Heap Sort
</div>

### Insertion Sort
**Time Complexity:** Average and worst - \(O(n^2)\), Best - \(O(n)\) when the array is nearly sorted.
Insertion Sort works by removing one element from the input data, finding the location it belongs within the sorted list, and inserting it there. It is much less efficient on larger lists than more advanced algorithms like quicksort, but it provides advantages for small arrays or arrays that are already substantially sorted.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="/assets/img/sorting_visualizer/insertionsort_screenshot.png" title="Insertion Sort" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Insertion Sort
</div>

### Selection Sort
**Time Complexity:** Always \(O(n^2)\).
Selection Sort improves on the simplicity of bubble sort by reducing the number of swaps required. It works by repeatedly selecting the smallest or largest element (depending on the sorting order) from the unsorted portion of the list and swapping it with the element at the beginning of the unsorted list. Despite its inefficiency, it's useful for its simplicity and minimal use of memory.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="/assets/img/sorting_visualizer/selectionsort_screenshot.png" title="Selection Sort" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Selection Sort
</div>
