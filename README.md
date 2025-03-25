# Enigma Machine Simulator

## Overview
This project implements a simplified Enigma machine simulator in Python, replicating the cryptographic device used during World War II. It includes key components like rotors, a plugboard, and a reflector, allowing users to encrypt and decrypt messages.

### Features
- **Rotors**: Three rotors with fixed wirings, rotating after each letter.
- **Plugboard**: Supports letter swaps (e.g., A↔B).
- **Reflector**: Fixed reflector (UKW-B) for letter pairing.
- **Encryption/Decryption**: Encrypts a message and decrypts it with the same settings.

### File Structure
- `enigma.py`: Core Enigma machine logic.
- `main.py`: Interactive script to run the simulator.
- `README.md`: Project documentation.

## Usage
1. **Requirements**: Python 3.x (no external libraries needed).
2. **Run**:
   ```bash
   python main.py
