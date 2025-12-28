# LaTeX Resume

A professional, ATS-compliant resume template built with LaTeX. This resume uses modern formatting with the Charter font and includes sections for experience, projects, education, and technical skills.

## Prerequisites

To compile this resume, you need a LaTeX distribution installed on your system:

- **macOS**: Install [MacTeX](https://www.tug.org/mactex/) or BasicTeX
- **Linux**: Install TeXLive (`sudo apt-get install texlive-full` on Ubuntu/Debian)
- **Windows**: Install [MiKTeX](https://miktex.org/) or TeXLive

## Compiling the Resume

### Using pdflatex (Command Line)

```bash
pdflatex resume.tex
```

This will generate a `resume.pdf` file in the same directory.

### Using an Online Editor

You can also use online LaTeX editors like [Overleaf](https://www.overleaf.com/) by uploading the `resume.tex` file.

## Resume Structure

The resume includes the following sections:

- **Heading**: Contact information with phone, email, LinkedIn, GitHub, and portfolio links
- **Experience**: Professional work history with detailed accomplishments
- **Projects**: Notable projects with technologies used
- **Education**: Academic background
- **Technical Skills**: Programming languages and frameworks

## Customization

### Personal Information

Update the heading section (lines 75-83) with your own information:

- Name
- Phone number
- Email address
- LinkedIn profile
- GitHub profile
- Portfolio website

### Content Sections

Each section uses custom commands for consistent formatting:

- `\resumeSubheading{Title}{Date}{Subtitle}{Location}` - For jobs and education
- `\resumeProjectHeading{Title}{Date}` - For projects
- `\resumeItem{Description}` - For bullet points

### Styling

- **Font**: Currently uses Charter font (line 25). Uncomment line 24 to use Fira Sans instead
- **Margins**: Adjust margins in lines 33-36
- **Colors**: Modify section title colors in line 44

## Features

- ✅ **ATS-Compliant**: Uses `\pdfgentounicode=1` for proper text extraction
- ✅ **FontAwesome Icons**: Includes icons for contact information
- ✅ **Single Page**: Optimized for a clean, one-page layout
- ✅ **Professional Typography**: Uses Charter font for readability

## License

Feel free to use this template for your own resume. No attribution required.
