<div align="center">
    <p align="center">
        <a href="https://github.com/cybersecurity-dev/awesome-elf-internals">
          <img width="13%" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/Tux.svg" />
        </a>
    </p>

# **`Awesome`** [ELF](https://wikipedia.org/wiki/Executable_and_Linkable_Format) (_[Executable and Linkable Format]()_) [Feature](https://wikipedia.org/wiki/Feature_(machine_learning)) [Extractor](https://wikipedia.org/wiki/Comparison_of_executable_file_formats) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
</div>

[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://elixir.bootlin.com/linux/v6.17/source)
[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://youtube.com/playlist?list=PL9V4Zu3RroiVlMaBS8X6_nkXz6FPyGa-O&si=-W_udRBVwMf6kdi5)
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)]()

<p align="center">
    <a href="https://github.com/cybersecurity-dev/"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/github.svg" alt="GitHub"></a>
    &nbsp;
    <a href="https://www.youtube.com/@CyberThreatDefense"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/youtube.svg" alt="YouTube"></a>
    &nbsp;
    <a href="https://cyberthreatdefence.com/my_awesome_lists"><img height="20" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/blog.svg" alt="My Awesome Lists"></a>
    <img src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/bar.gif">
</p>

```mermaid
mindmap
  root((ELF Features))
    Static Features
      ELF Header
        Class
        Endianness
        Entry Point
        Machine
      Program Headers
      Section Headers
      Dynamic Symbols
      Relocations
      Shared Libraries

    Structural Features
      File Size
      Segment Count
      Section Count
      Entry Point Offset
      Memory Layout
      Permissions

    Behavioral Indicators
      Network APIs
      File APIs
      Process APIs
      Syscalls
      Persistence
      Privilege Escalation

    Metadata Features
      Architecture
      ABI
      Compiler
      Build ID
      Debug Symbols

    Strings Features
      URLs
      IP Addresses
      Domains
      Commands
      File Paths
      Emails

    Entropy Features
      Global Entropy
      Text Entropy
      Data Entropy
      Packed Sections
      Compressed Sections

    Graph Features
      Call Graph
      CFG
      DFG
      PDG
      Function Dependencies
      Interprocedural Graph

    Opcode Features
      Opcodes
      N-grams
      Instruction Frequency
      Basic Block Statistics

    Security Features
      NX
      PIE
      RELRO
      Stack Canary
      ASLR Compatibility
      Fortify Source

    ML Ready Features
      Numeric
      Categorical
      Binary Flags
      Statistical
      Graph Embeddings
```

## 📖 Contents
- [My Other Awesome Lists](#my-other-awesome-lists)
- [Contributing](#contributing)
- [Contributors](#contributors)


## ELF parsing tools
* [LIEF](https://lief.re/) - **`LIEF`** (Library to Instrument Executable Formats) project aims at providing a cross platform library to parse, modify and abstract ELF, PE and MachO formats.
* [pyelftools ](https://github.com/eliben/pyelftools) - **`pyelftools`** is a pure-Python library for parsing and analyzing ELF files and DWARF debugging information.
* [readelf](https://man7.org/linux/man-pages/man1/readelf.1.html) - **`readelf`** displays information about one or more ELF format object files.

## 1. Raw Binary Features
* Byte Histogram
* Byte Entropy
* Byte N-grams
* Image Representation Features

## 2. ELF Parsing Features
* ELF Header
* Program Header Table
* Section Header Table
* Dynamic Linking Information

## 3. Symbol-Based Features
* Imported Functions
* Exported Functions
* Dynamic Symbols
* Relocations

## 4. String-Based Features
* URLs
* Domains
* IP Addresses
* Commands
* File Paths

## 5. Opcode Features
* Instruction Frequency
* Opcode N-Grams
* Control Instructions
* Arithmetic Instructions

## 6. Security Hardening Features
* NX Enabled
* PIE Enabled
* RELRO Level
* Stack Canary
* Fortify Source

## 7. Graph-Based Features
* Call Graph (CG)
* Control Flow Graph (CFG)
* Data Flow Graph (DFG)
* Program Dependency Graph (PDG)
* Code Property Graph (CPG)

## 8. Statistical Features
* Function Count
* Basic Block Count
* Cyclomatic Complexity
* Average Function Size
* Section Statistics

## 9. Malware-Specific Indicators
* Shell Execution Functions
* Network Communication Functions
* Crypto APIs
* Anti-Debugging Artifacts
* Persistence Mechanisms
* Privilege Escalation Indicators

## 10. GNN-Oriented Graph Features
* Node Degree
* Centrality Metrics
* Graph Density
* Graph Embeddings
* Weisfeiler-Lehman Features
* Graph2Vec Features
* Node2Vec Features

## 

### My Other Awesome Lists
You can access the my other awesome lists [here](https://cyberthreatdefence.com/my_awesome_lists)

### Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors

[Thanks goes to these contributors](https://github.com/cybersecurity-dev/awesome-smartcontract-datasets/graphs/contributors)!

[🔼 Back to top](#awesome-elf-feature-extractor-)