# Ant Build Script for QuickSort and Binary Search Java Project

## Overview
This project provides an Ant build script for a Java project that implements the QuickSort algorithm to sort an array and performs Binary searching for a number provided by the program user.

## Project Structure
The project consists of the following classes:
- `BinarySearch.java`: Implements Binary Search algorithm to find a target number in the sorted array.
- `QuickSort.java`: Implements the QuickSort algorithm to sort an array.
- `Runner.java`: The main class takes user input, sorts the array using QuickSort, and performs Binary Search.
  <span style="color: blue; font-size: 20px;">
  project-root
├── src
│   ├── searching
│   │   └── BinarySearch.java
│   ├── sorting
│   │   └── QuickSort.java
│   └── main
│       └── app
│           └── Runner.java
└── build.xml

  </span>
  project-root<br>
├── src<br>
│   ├── searching<br>
│   │   └── BinarySearch.java<br>
│   ├── sorting<br>
│   │   └── QuickSort.java<br>
│   └── main<br>
│       └── app<br>
│           └── Runner.java<br>
└── build.xml<br>

## Usage
To compile and run the project using the provided Ant build script, follow these steps:
1. Clone the repository: `git clone https://github.com/your-username/ant-build.git`
2. Navigate to the project directory: `cd ant-build`
3. Execute the Ant build script: `ant`
4. Run the compiled program: `java -jar jar/Main.jar`

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or create a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
