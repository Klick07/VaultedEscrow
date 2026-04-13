# VaultedEscrow Frontend

A modern web app for milestone-based escrow contracts, built for Indian freelancers and agencies. Features a 3D morphing particle background, automated milestone management, and system-driven trust.

## Features

- 3D morphing particle hero section (Three.js + React Three Fiber)
- Automated escrow workflow with milestone contracts
- Transparent, rule-based system for dispute resolution
- Modern, responsive UI with Tailwind CSS
- Lucide React icons

## Getting Started

### Prerequisites

- Node.js (v16+ recommended)
- npm or yarn

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/vaultedescrow-frontend.git
   cd vaultedescrow-frontend
   ```

2. **Install dependencies:**
   ```sh
   npm install
   # or
   yarn install
   ```

3. **Download 3D Models:**

   Download the following 3D models and place the `.glb` files in your `public` directory:

   - [Space Station 3](https://sketchfab.com/3d-models/space-station-3-a7a6ad10261149cab31aa394bfcf8940)
   - [Chernovan Nemesis](https://sketchfab.com/3d-models/chernovan-nemesis-c6c91c73e93444f4b72d6c24db778e73)

   > **Note:** Make sure the downloaded files are named as referenced in the code (e.g., `space_station-transformed.glb`, `vault.glb`, etc.).

4. **Start the development server:**
   ```sh
   npm run dev
   # or
   yarn dev
   ```

5. **Open in browser:**
   Visit [http://localhost:5173](http://localhost:5173) (or the port shown in your terminal).

## Usage

- Explore the interactive 3D hero section.
- Review the milestone-based escrow workflow.
- See system-driven trust and transparency in action.

## Dependencies

- [React](https://reactjs.org/)
- [@react-three/fiber](https://docs.pmnd.rs/react-three-fiber/)
- [@react-three/drei](https://docs.pmnd.rs/drei/introduction)
- [lucide-react](https://lucide.dev/)
- [Tailwind CSS](https://tailwindcss.com/)

## License

This project is for educational/demo purposes. Please respect the licenses of any 3D models used.

---

**3D Model Credits:**

- [Space Station 3](https://sketchfab.com/3d-models/space-station-3-a7a6ad10261149cab31aa394bfcf8940) on Sketchfab  
- [Chernovan Nemesis](https://sketchfab.com/3d-models/chernovan-nemesis-c6c91c73e93444f4b72d6c24db778e73) on Sketchfab
