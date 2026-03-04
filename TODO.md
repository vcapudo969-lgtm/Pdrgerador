# Task: Gerador de Keys Implementation

## Plan
- [ ] Database Setup
  - [ ] Initialize Supabase `supabase_init`
  - [ ] Create tables: `profiles`, `login_versions`, `validity_options`, `generated_keys`, `transactions`, `complaints`, `api_keys`
  - [ ] Seed data for `login_versions` and `validity_options`
- [ ] Auth & Layout
  - [ ] Configure `AuthContext.tsx` and `RouteGuard.tsx`
  - [ ] Update `index.css` and `tailwind.config.js` for the dark theme
  - [ ] Create `Sidebar` and `DashboardLayout` components
- [ ] Pages Implementation
  - [ ] Login Page
  - [ ] Dashboard Page (Principal)
  - [ ] Generate Keys Page (Keys)
  - [ ] Manage Keys Page (Keys)
  - [ ] API Keys & Docs Page (API)
  - [ ] Wallet & Transfer Page (Carteira)
  - [ ] Profile, Affiliate, Complaints Pages (Perfil)
- [ ] Final Polish
  - [ ] Linting and bug fixes
  - [ ] Image replacement with `image_search`

## Notes
- Theme: Dark background, purple/green accents.
- Language: Portuguese UI, English code comments.
- Must use Supabase for everything.
