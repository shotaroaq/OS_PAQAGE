# OS-PAQAGE

"[Open Source microwave Packaging for quantum systems (OS-PAQAGE)](https://doi.org/10.5281/zenodo.18399469)" is a collection of PCB and magnetic-shielded sample-holder designs intended primarily for microwave-frequency use. These designs were developed mainly at RIKEN in Japan and are widely used by Japanese research institutes and universities. Using this package, measurements of superconducting qubits with energy relaxation times exceeding 400 us [1] and observations of internal Q factors above 1e7 in superconducting resonators at the single-photon level have been reported [2].

In fundamental research, there are still many situations where small samples are studied but a clean electromagnetic environment is required. To broaden the available options for building such measurement environments, we decided to release the contents of this repository as open source.

[1] [A. Noguchi, et al. "High-performance transmon qubits with an epitaxially grown TiN film on Si (100) substrate." 2023 APS March Meeting. 2023.](https://meetings.aps.org/Meeting/MAR23/Session/M73.5)
[2] [Y. Tominaga, et al. "Intrinsic quality factors approaching 10 million in superconducting planar resonators enabled by spiral geometry." EPJ Quantum Technology 12.1 (2025): 60.](https://link.springer.com/article/10.1140/epjqt/s40507-025-00367-w)

## Usage
Please place an order for the jigs with a nearby factory. Assembly instructions are provided in *doc/pcb_sample_holder_instructions.pdf*.
In our case, we outsource PCB manufacturing to KANSAI DENSHI INDUSTRIES.

## License
This repository is released under the MIT License. See `LICENSE`.

## Citation
If you use the contents of this repository, please cite the project in the following format:

```
@Misc{OS-PAQAGE,
  author = {Shirai, Shotaro and Noguchi, Atsushi},
  title = {{OS-PAQAGE}: A open source microwave packaging for quantum systems},
  year = {2025--},
  url = "https://doi.org/10.5281/zenodo.18399469",
  note = {[Online; accessed <today>]}
}
```

## Acknowledgements
This work has been supported by funding from JST Moonshot R&D Program (Grant Number JPMJMS2067)

