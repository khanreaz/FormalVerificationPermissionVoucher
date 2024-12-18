# Academic Paper Repository

This repository contains the source code and supplementary materials for the academic paper titled: **Formal Verification of Permission Voucher Protocol**.

## Overview

This repository includes:
- Source code for the paper's implementation.
- Tamarin Prover scripts for protocol verification.
- Generated results from the verification process.
- Documentation and supplementary materials.

## Repository Structure

```
├── code/                   # Source code for the implementation
├── tamarin-scripts/        # Tamarin Prover models and scripts
├── results/                # Verification results and analysis
├── docs/                   # Documentation and supplementary materials
├── README.md               # This README file
└── LICENSE                 # Licensing information
```

## Requirements

The project uses the following dependencies:
- Tamarin Prover (>=1.6.0)

Ensure that Tamarin Prover is installed and accessible from your command line.

## Usage

### Running the Tamarin Scripts
1. Clone this repository:
   ```bash
   git clone https://github.com/khanreaz/FormalVerificationPermissionVoucher
   cd FormalVerificationPermissionVoucher
   ```
2. Navigate to the `tamarin-scripts/` directory:
   ```bash
   cd tamarin-scripts
   ```
3. Run a specific Tamarin script:
   ```bash
   tamarin-prover --prove your_script.spthy
   ```

### Viewing Results
- Verification results will be output to the `results/` directory.
- Use the Tamarin GUI to explore proof states if needed:
   ```bash
   tamarin-prover interactive your_script.spthy
   ```

### Additional Notes
- Detailed instructions for each script are available in the `docs/` directory.

## Citation

If you use this repository in your work, please cite our paper:
```
@article{your-citation-key,
  title={Formal Verification of Permission Voucher Protocol},
  author={Khan Reaz and Gerhard Wunder},
  year={2024}
}
```

## License

This repository is licensed under the GPLv3. See the `LICENSE` file for details.


*We welcome contributions and discussions to improve or extend the project!*
