# MM-Fit Web

Browser-based version of **MM-Fit**, a teaching tool for Michaelis–Menten enzyme kinetics.
You can find a standalone version [here](https://github.com/JMB-Scripts/Michaelis-Menten)

## Use

Open the application in a web browser:

**https://JMB-Scripts.github.io/MM-Fit-Web/**

No installation is required. Calculations are performed directly in the browser using PyScript/Pyodide, NumPy and SciPy.

### 📱 Smartphone & OCR Support
The web application automatically adapts to small screens. When opened on a smartphone, it provides a touch-optimized interface designed for the lab bench. You don't even need to type your data: just use your phone's built-in camera OCR (like Apple Live Text or Google Lens) to scan a table from a piece of paper or a computer screen, and paste it directly into the app to get your Michaelis-Menten fit instantly.

## Workflow
1. **1- Paste from Excel** — paste tab-separated kinetic data ([S]0 v01 v02 ...).
2. **2-MM-Fit** — perform Michaelis–Menten fitting and display residuals with the ±10% tolerance region.
4. **3-LB plot** — display the Lineweaver–Burk transformation and linear regression.
6. Use the **Exclude** checkbox on individual data points when a point should not be included in the fit.
7. **Set Units** you can now add units with upperscript (^) or lowerscript (_) i.e. mol.L^-1 gives mol.L<sup>-1</sup>
8. Use the **Print report** to print the report
9. **Reset** — restore the default data.

## Screenshot

<img width="1703" height="944" alt="image" src="https://github.com/user-attachments/assets/dae79975-eb26-44d6-8fc1-4a44593db927" />


## Technology

- HTML / CSS / JavaScript
- PyScript / Pyodide
- NumPy
- SciPy
- Plotly
- GitHub Pages

Designed for teaching enzyme kinetics in the **UGA**
