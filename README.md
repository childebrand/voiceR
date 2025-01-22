# voiceR: Voice Analytics for Social Scientists 🎤

[![CRAN](https://www.r-pkg.org/badges/version/voiceR)](https://cran.r-project.org/package=voiceR)

voiceR is an R package that simplifies voice analytics for behavioral and social science research. We provide an easy-to-use interface for processing, analyzing, and reporting voice and audio recording data.

## Key Features

- 🔍 Automated extraction of key vocal features (pitch, loudness, etc.)
- 📊 Built-in statistical analysis and visualization tools
- 📝 Automatic APA-formatted report generation
- ⚡ Parallel processing for handling multiple audio files
- 🖥️ Interactive Shiny app for no-code analysis

## Quick Start

```r
# Install from CRAN
install.packages("voiceR")

# Launch the Shiny app
library(voiceR)
voiceRApp()

# Or analyze files programmatically
results <- autoExtract(path = "path/to/audio/files")
```

## Learn More

- [Documentation](https://cran.r-project.org/package=voiceR)
- [Methodology Paper](https://doi.org/10.1016/j.jbusres.2020.09.020)

## Authors

- Francesc Busquet
- Christian Hildebrand
