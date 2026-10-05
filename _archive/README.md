# _archive

Folder freeze. Project paused, not deleted.

## office-suite
- Frozen: 2026-10-04
- Reason: Clone 1:1 MS Office tidak viable solo vs Big Tech. NOL AI integration, diferensiasi lemah.
- Stack: Turbo+pnpm+React18+Vite6+TS5.7, CRDT collab, 4 engines (word/excel/ppt/visio)
- Revive if: pivot ke niche (E2EE / SOC-report / air-gapped) atau extract micro-tool.
- Restore: Move-Item _archive\office-suite .

## litebrowse
- Frozen: 2026-10-04
- Reason: Browser minimal vs Chrome/Edge head-on tidak viable solo. Niche umum overcrowded.
- Stack: .NET 10 + WebView2 1.0.4078.44 + WPF + SQLite + 7 src/8 test, MSIX, AGENTS multi-role
- Revive if: pivot security-browser (pentest/kiosk/air-gapped, zero-telemetry) atau extract component.
- Restore: Move-Item _archive\litebrowse .

## app-ai-workspace
- Frozen: 2026-10-04
- Reason: Enterprise AI platform crowded (LangChain/Dify/CrewAI/AutoGen/Copilot Studio). Repo status NOT READY.
- Stack: pnpm/Turbo/Prisma/Next16/Kafka/Postgres/Redis/MinIO, 12 services
- Revive if: niche governance/policy/evidence security (align ocysec), bukan platform generic.
- Restore: Move-Item _archive\app-ai-workspace . ; pnpm install

## app-sosmed
- Frozen: 2026-10-04
- Reason: Sosmed crowded (Meta/X/TikTok). Skeleton kosong, nol source code.
- Status: dist/win-unpacked + electron node_modules only. 2 file .asar locked by AV/indexer.
- Cleanup: reboot + rmdir /s /q app-sosmed (root folder tersisa, harmless).
- Restore: N/A - buat baru.
