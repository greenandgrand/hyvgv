# BaseMint – Farcaster Miniapps (Base L2)

Starter kit sederhana untuk Miniapps Farcaster bernama **BaseMint**.
Fitur: Connect Wallet, NFT preview, tombol Mint, status transaksi, dan riwayat mint.
Frontend: React + Vite + Tailwind + wagmi/viem. Kontrak: ERC-721 sederhana.

## Quick start
1) Install pnpm: https://pnpm.io/installation
2) `pnpm -w i`
3) Deploy kontrak (lihat /contracts)
4) Set `CONTRACT_ADDRESS` di `apps/frontend/src/lib/contract.ts`
5) Jalankan: `cd apps/frontend && pnpm dev`
