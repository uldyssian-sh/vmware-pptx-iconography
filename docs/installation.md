# Installation Guide

## Quick Start

### Option 1: Direct Download
1. Visit the [Releases page](https://github.com/uldyssian-sh/vmware-pptx-iconography/releases)
2. Download the latest release ZIP file
3. Extract to your desired location

### Option 2: Git Clone
```bash
git clone https://github.com/uldyssian-sh/vmware-pptx-iconography.git
cd vmware-pptx-iconography
```

## PowerPoint Integration

### Installing Icons
1. Open PowerPoint
2. Go to Insert > Icons > Import Icons
3. Browse to the `icons/` directory
4. Select desired icons and import

### Installing Templates
1. Copy template files to your PowerPoint templates directory:
   - **Windows**: `%USERPROFILE%\Documents\Custom Office Templates`
   - **macOS**: `~/Library/Group Containers/UBF8T346G9.Office/User Content/Templates`
2. Restart PowerPoint
3. Templates will appear in File > New > Personal

## System Requirements

### PowerPoint Compatibility
- Microsoft PowerPoint 2016 or later
- PowerPoint for Microsoft 365
- PowerPoint Online (limited features)

### Supported Operating Systems
- Windows 10/11
- macOS 10.14 or later
- Web browsers (for PowerPoint Online)

## Verification

After installation, verify by:
1. Opening PowerPoint
2. Creating a new presentation
3. Checking if templates appear in File > New > Personal
4. Testing icon import functionality

## Troubleshooting

### Icons Not Displaying
- Ensure PowerPoint supports SVG format (2016+)
- Try PNG format as alternative
- Check file permissions

### Templates Not Available
- Verify template directory path
- Restart PowerPoint after copying files
- Check file format (.potx for templates)

### Performance Issues
- Use PNG instead of SVG for large presentations
- Optimize image sizes before importing
