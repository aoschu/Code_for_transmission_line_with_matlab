# Code_for_transmission_line_with_matlab


# OFDM-based Digital Communication System

Welcome to the OFDM-based Digital Communication System repository! This MATLAB project demonstrates the transmission and reception of digital data using Orthogonal Frequency Division Multiplexing (OFDM) along with key techniques including Hamming coding, symbol mapping, pilot insertion, and channel simulation. Additionally, the impact of impairments in the transmission hardware is explored.

## Features

- **Frame Generation:** Random data frames are generated for transmission.
- **Hamming Coding:** Data is encoded using Hamming codes for error correction.
- **Mapping to Symbols:** Encoded data is mapped to complex symbols.
- **Pilot Insertion:** Pilot symbols are inserted to aid in channel estimation.
- **OFDM Modulation:** Symbols are modulated using OFDM for efficient spectrum usage.


## Usage

1. Clone this repository to your local machine.
2. Open MATLAB and navigate to the repository folder.
3. Configure system parameters such as SNR, number of subcarriers, etc. in `main.m`.
4. Run the `main.m` script to execute the OFDM communication system.
6. Check the receiver and channel folders, download them all, and run the main.m file.
5. The script will display the Bit Error Rate (BER) as an indicator of system performance.

## Contents

- `main.m`: Main script to run the OFDM communication system.
- `hamming_encode.m`: Hamming encoding function.
- `insert_pilots.m`: Pilot insertion function.
- `map_to_symbols.m`: Mapping data to symbols function.
- `ofdm_modulation.m`: OFDM modulation function.
- `add_awgn.m`: Adding AWGN (noise) to the signal.
- `ofdm_demodulation.m`: OFDM demodulation function.
- `demap_symbols.m`: Demapping symbols back to data function.
- `remove_pilots.m`: Pilot removal function.
- `hamming_decode.m`: Hamming decoding function.
- `calculate_ber.m`: Bit Error Rate calculation function.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer

This project is intended for educational and illustrative purposes. It provides a simplified simulation of an OFDM communication system and does not represent a production-ready solution.

Feel free to explore, experiment, and adapt the code to your needs. If you find this project useful, consider giving it a star on GitHub!
