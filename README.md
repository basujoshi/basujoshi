KhataPro v7 - Quantity Units & Logout Confirmation Update

Added:
- Owner customer ledger item entry supports pcs, gm and kg.
- Quick quantity buttons: 50gm, 100gm, 150gm, 250gm, 500gm, 1kg, 1pc, 2pcs.
- 1000gm is normalized/displayed as 1 kg; 1500gm displays as 1.5 kg.
- For weight entries, MRP is treated as price per kg. Example: MRP 200/kg + 50gm = total 10.
- Piece entries calculate MRP x pieces. Example: MRP 50 + 2pcs = total 100.
- Quantity unit and display are saved with each transaction and shown in the owner/customer portal history.
- Existing transactions remain readable; old transactions without a unit are treated as pcs.
- Owner dashboard Logout now asks for confirmation before signing out.

Firebase data remains under the authenticated owner's UID.
