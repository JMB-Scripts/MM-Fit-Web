# MM-Fit Web

Browser-based version of **MM-Fit**, a teaching tool for Michaelis–Menten enzyme kinetics.

## Use

Open the application in a web browser:

**https://JMB-Scripts.github.io/MM-Fit-Web/**

No installation is required. Calculations are performed directly in the browser using PyScript/Pyodide, NumPy and SciPy.

## Workflow

1. **Paste from Excel** — paste tab-separated kinetic data.
2. Select the series to analyse.
3. **MM-Fit** — perform Michaelis–Menten fitting and display residuals with the ±10% tolerance region.
4. **LB plot** — display the Lineweaver–Burk transformation and linear regression.
5. Use the **Exclude** checkbox on individual data points when a point should not be included in the fit.
6. **Reset** — restore the default data.

Excluded points are retained in the table and shown as crosses on the MM plot. They are ignored by both MM and Lineweaver–Burk analyses.

## Local testing

From the repository directory:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/index.html
```

## Technology

- HTML / CSS / JavaScript
- PyScript / Pyodide
- NumPy
- SciPy
- Plotly
- GitHub Pages

Designed for teaching enzyme kinetics in the **UGA Master Biochemistry and Structure** programme.
