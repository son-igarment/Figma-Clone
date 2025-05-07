# Figma Clone by Phạm Lê Ngọc Sơn

## Overview
This project is a Figma clone application developed by Phạm Lê Ngọc Sơn. It replicates the core features of Figma, providing a collaborative design tool with real-time editing capabilities. The application is built using Next.js, Fabric.js for canvas manipulation, and Liveblocks for real-time collaboration.

## Project Structure

```
figma-clone/
├── app/                    # Main application code
│   ├── App.tsx             # Main application component
│   ├── Room.tsx            # Room component for collaboration
│   ├── globals.css         # Global styles
│   ├── layout.tsx          # Root layout component
│   └── page.tsx            # Home page component
├── components/             # UI components
│   ├── cursor/             # Cursor components for collaboration
│   ├── comments/           # Comments functionality
│   ├── Live.tsx            # Live collaboration component
│   ├── Navbar.tsx          # Application navbar
│   ├── LeftSidebar.tsx     # Left sidebar with tools
│   └── RightSidebar.tsx    # Right sidebar with properties
├── constants/              # Constants used throughout the app
├── hooks/                  # Custom React hooks
├── lib/                    # Utility functions
├── public/                 # Static assets
└── types/                  # TypeScript type definitions
```

## Key Features

1. **Canvas Editing**: Create and manipulate various shapes including rectangles, circles, and triangles.
2. **Text Editing**: Add and format text elements with various fonts and styles.
3. **Image Upload**: Upload and manipulate images on the canvas.
4. **Real-time Collaboration**: Multiple users can work on the same design simultaneously.
5. **Comments**: Add comments to designs for feedback.
6. **Live Cursors**: See where other users are working in real-time.
7. **Undo/Redo**: Full support for undo and redo operations.
8. **Responsive Design**: Works across different device sizes.

## Technologies Used

- **Frontend**: Next.js 14, React 18, TypeScript
- **Canvas Manipulation**: Fabric.js
- **Real-time Collaboration**: Liveblocks
- **Styling**: Tailwind CSS
- **UI Components**: Radix UI
- **Icons**: Lucide React

## Getting Started

### Prerequisites
- Node.js 18 or later
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/username/figma-clone.git
   cd figma-clone
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Set up environment variables:
   Create a `.env.local` file in the root directory and add your Liveblocks API key:
   ```
   NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=your_liveblocks_public_key
   ```

4. Run the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. Open your browser and navigate to `http://localhost:3000`

## Usage

1. **Creating Shapes**: Select a shape from the left sidebar and click and drag on the canvas to create it.
2. **Text**: Click the text tool and then click on the canvas to add text.
3. **Properties**: Use the right sidebar to modify the properties of selected elements.
4. **Collaboration**: Share the URL with collaborators to work together in real-time.
5. **Comments**: Use the comment tool to add feedback to specific areas of the design.

## Contact

For any inquiries, please contact Phạm Lê Ngọc Sơn.

## License

This project is created by Phạm Lê Ngọc Sơn, all rights reserved.

---

© 2024 Phạm Lê Ngọc Sơn. All Rights Reserved.
