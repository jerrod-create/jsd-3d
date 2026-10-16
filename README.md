# Jones Steel Design - 3D assembly viewers

Live at **https://3d.jonessteeldesign.com** (GitHub Pages).

Each job has its own folder (`/<job>/`). The QR code in the title block of every JSD assembly drawing opens
`https://3d.jonessteeldesign.com/<job>/#<ASSEMBLY_MARK>`, which shows that assembly in 3D with part, hole and weld callouts.

- `index.html` - list of jobs (generated from `jobs.json`)
- `<job>/index.html` - self-contained viewer built from the Tekla export macro "Claude - Sheet Data Export"
