# Sorting Visualizer with SDL2 Library

![Sorting Visualizer](/img/demo.png)

## Description

This is a Sorting Visualizer implemented in C++ using the SDL2 Library. It allows users to visualize various sorting algorithms on a graphical window. A sorting algorithm is an algorithm that puts the elements of a list in a certain order. While there are a large number of sorting algorithms, in practical implementations, a few algorithms predominate.

In this project, we visualize the working of popular sorting algorithms such as:
- Selection Sort
- Insertion Sort
- Bubble Sort
- Merge Sort
- Quick Sort
- Heap Sort

The visualizer provides a fixed list size of 130 elements. Users can randomize the list and select any type of sorting algorithm from the available options. All sorting algorithms sort the elements in ascending order.

Please note that the sorting time being visualized for an algorithm is not exactly the same as their actual time complexities. The relatively faster algorithms like Merge Sort have been delayed for visualization purposes.

## Usage

1. Clone the repository to your local machine.
2. Compile the source code using a C++ compiler with the SDL2 library installed.
3. Run the executable file.
4. Use the following controls to interact with the Sorting Visualizer:
    - Press `0` to generate a different randomized list
    - Press `1` to start Selection Sort
    - Press `2` to start Insertion Sort
    - Press `3` to start Bubble Sort
    - Press `4` to start Merge Sort
    - Press `5` to start Quick Sort
    - Press `6` to start Heap Sort
    - Press `q` to exit the Sorting Visualizer

## Animation Speed

The animation speed of the sorting process can be adjusted by changing the `animationSpeed` variable in the source code. The default value is set to `40`, but users can modify it to increase or decrease the animation speed as desired.

## Future Improvements

- GUI enhancements: Adding buttons and sliders for better user interaction.
- Dynamic array size: Allowing users to increase or decrease the size of the array.
- Additional sorting algorithms: Implementing more sorting algorithms for visualization.
- Performance optimizations: Improving the efficiency of the visualization process.
- Color customization: Allowing users to change the background and rectangle colors.
