# FileLab OS

A small animated visual explainer for a university Operating Systems seminar on file-system implementation and recovery.

## Includes
- Three guided chapters: Disk allocation, Directory search, Crash & recovery.
- Contiguous, linked, and indexed allocation with animated disk blocks and pointer connections.
- Linear directory scan and hash-bucket lookup with a visible collision.
- A five-step save sequence, crash interruption, and three simplified recovery demonstrations.
- Shared play/pause, replay, previous/next, progress, responsive layout, and reduced-motion support.

## Stack
React + TypeScript, Vite, Tailwind CSS, Motion for React (`motion/react`), Lucide icons. No backend or external APIs.

## Run locally
```bash
npm install
npm run dev
```

## Verify
```bash
npm run lint
npm run build
```
