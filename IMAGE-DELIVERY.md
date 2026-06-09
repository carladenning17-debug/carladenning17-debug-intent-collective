# Intent Collective Image Delivery

## Generated Images

### 1. Open Graph Image (`og-image.png`)
- **Dimensions**: 1200×630px
- **Purpose**: Social media sharing preview
- **Format**: PNG
- **Description**: Professional modern Open Graph image with teal and coral brand colors, abstract connection network background, centered typography with company mission statement
- **File Size**: 611KB

### 2. Logo Image (`logo.png`)
- **Dimensions**: 512×512px 
- **Purpose**: Structured data/JSON-LD logo reference
- **Format**: PNG
- **Description**: Professional logo based on SVG design, circular connection network pattern with central orange node, surrounding teal nodes, connecting lines and gradient glow effect
- **File Size**: 374KB

### 3. Social Media Image (`images/social/social-share-square.png`)
- **Dimensions**: 1200×1200px
- **Purpose**: Social media profiles and sharing
- **Format**: PNG
- **Description**: Square social media banner with professional modern design, teal and coral color scheme, abstract connection network background, clean minimalist layout
- **File Size**: 700KB

## Generation Details

All images were generated using Replicate's flux-schnell model with the following brand specifications:

### Brand Colors Used:
- Primary Teal: `#0D9488`
- Primary Coral: `#F97316` 
- Accent Gold: `#F59E0B`
- Accent Mint: `#34D399`
- Background Off-White: `#FAFAF9`

### Design Elements:
- Abstract connection network pattern
- Modern sans-serif typography
- Clean minimalist layout
- Corporate professional style
- Gradient lighting effects

## Usage Notes

1. **Open Graph Image**: Reference in `<meta property="og:image">` tag for social sharing
2. **Logo Image**: Used in JSON-LD structured data for SEO
3. **Social Media Image**: Can be used for social media profiles, posts, and marketing materials

## Image Optimization

For production use, consider:
- Compressing PNG files with tools like ImageOptim or Squoosh
- Converting to WebP format for better web performance
- Creating responsive versions for different device sizes

## Files Created
```
/tmp/opencode/intent-collective-website/
├── og-image.png
├── logo.png
└── images/social/
    └── social-share-square.png
```

## Model Specifications
- **Model**: `black-forest-labs/flux-schnell`
- **Version**: `c846a69991daf4c0e5d016514849d14ee5b2e6846ce6b9d6f21369e564cfe51e`
- **Generation Time**: ~2-3 seconds per image
- **Total Images Generated**: 3
- **Total File Size**: ~1.7MB

Generated on: 2026-06-09 14:39 UTC