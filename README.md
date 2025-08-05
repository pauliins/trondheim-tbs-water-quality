🌊 Water Quality Data – Trondheim Biological Station

This repository contains water quality data collected at the **Trondheim Biological Station pier**, at approximately **0.5 m depth**. Measurements were taken using:

- **Ecotriple multiparameter probe**
- **HOBO CTD logger**

📅 Sampling Details

- **Location**: Trondheim Biological Station pier  
- **Depth**: ~0.5 meters  
- **Frequency**: Weekly sensor cleaning and maintenance  
- **Calibration**: Per Ecotriple manufacturer coefficients

📁 Repository Contents

```
├── data/                    # Raw and processed water quality data
│   ├── raw/           # Data from Ecotriple probe and from HOBO CTD logger
│   └── calibration_files            # calibrated Ecotriple data
├── notebooks/                # Data processing and visualization scripts
├── metadata/                 # Sensor metadata and deployment notes
└── README.md                # Project overview and documentation
```

📊 Parameters Measured

Typical parameters include (depending on sensor configuration):

- Temperature  
- Conductivity  
- Chlorophyll fluorescence
- cDOM fluorescence
- turbidity

 🛠️ Notes

- Sensors are cleaned weekly to ensure data quality.
- Calibration is performed according to manufacturer coefficients, infrequent in-situ samplings are conducted to check consistency with analytical methods
- Data is collected for research and monitoring purposes.

---

🤝 Contributing

We welcome contributions! If you have relevant data, improvements to scripts, or suggestions, feel free to:

1. Fork the repository  
2. Create a new branch  
3. Commit your changes  
4. Open a pull request

Please include a brief description of your changes and any relevant context.

---

📚 Citation

If you use this dataset in your research or publication, please cite it as:

> Salmi, P. , Børgum, R. & Fragoso, G. et al. (2025). *Water Quality Data from Trondheim Biological Station Pier*. GitHub repository: https://github.com/pauliins/trondheim-tbs-water-quality
