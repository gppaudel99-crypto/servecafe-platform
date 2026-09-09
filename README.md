# ServeCafe Platform

## Premium Restaurant, Membership, Ranking & Rewards Platform

A modern, production-ready web application built with Next.js, TypeScript, Tailwind CSS, and shadcn/ui.

### Features

- 🏪 **Restaurant Management** - Menu, ordering, and delivery/pickup
- 👥 **Membership System** - Package-based member onboarding
- 🏔️ **Himalayan Rank System** - 6-tier rank progression (Annapurna to Everest Star)
- 🎁 **Rewards Program** - Multi-level reward calculations and tracking
- 🌳 **Referral & Team Tree** - Interactive genealogy and team visualization
- 📊 **Admin Dashboard** - Complete management interface
- 🔐 **User Authentication** - Secure login and registration
- 📱 **Fully Responsive** - Mobile-first design
- ✨ **Smooth Animations** - Framer Motion animations
- 🎨 **Premium UI** - shadcn/ui components and custom styling

### Tech Stack

- **Framework:** Next.js 14 with App Router
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **Components:** shadcn/ui
- **Icons:** Lucide Icons
- **Animations:** Framer Motion
- **State:** Zustand
- **Forms:** React Hook Form + Zod
- **HTTP:** Axios

### Project Structure

```
src/
├── app/                    # Next.js app router pages
├── components/             # Reusable React components
├── lib/                    # Utility functions and helpers
├── types/                  # TypeScript type definitions
├── styles/                 # Global styles
├── hooks/                  # Custom React hooks
├── store/                  # Zustand state management
├── api/                    # API client functions
├── config/                 # Configuration files
└── utils/                  # Utility functions
```

### Getting Started

#### Prerequisites

- Node.js 18+
- npm or yarn

#### Installation

```bash
# Clone the repository
git clone https://github.com/gppaudel99-crypto/servecafe-platform.git
cd servecafe-platform

# Install dependencies
npm install

# Create environment file
cp .env.example .env.local

# Update .env.local with your configuration
```

#### Development

```bash
# Start development server
npm run dev

# Open http://localhost:3000 in your browser
```

#### Production

```bash
# Build for production
npm run build

# Start production server
npm start
```

### Database Schema

The platform is designed to work with Supabase or Firebase.

**Core Tables:**
- `users` - User accounts
- `profiles` - User profiles
- `memberships` - Membership records
- `packages` - Membership packages
- `ranks` - Rank definitions (Annapurna Star, etc.)
- `qualifications` - Qualification records
- `referrals` - Referral tracking
- `teams` - Team/genealogy data
- `rewards` - Reward records
- `orders` - Food orders
- `menu_items` - Restaurant menu
- `locations` - Restaurant locations
- `gallery` - Image gallery
- `testimonials` - User testimonials

### Key Features

#### Rank System

1. **Annapurna Star** - Entry level (NPR 21,000 entry package)
2. **Manaslu Star** - 2 qualified members
3. **Dhaulagiri Star** - 5 qualifications
4. **Makalu Star** - 7 qualifications
5. **Kanchenjunga Star** - 9 qualifications
6. **Everest Star** - 11 qualifications (highest)

#### Membership Package

- **Price:** NPR 21,000
- **Benefits:** Access to all ServeCafe services
- **Qualification:** Eligible for rank progression

#### Reward Categories

- Direct referral rewards
- Team rewards
- Generation rewards
- Rank-based benefits
- Pension/long-term rewards

### Admin Dashboard

Access to manage:
- Users and memberships
- Ranks and qualifications
- Rewards and referrals
- Menu and orders
- Gallery and testimonials
- Locations and contact messages
- Reports and settings

### Security

- Role-based access control (Member, Staff, Admin, Super Admin)
- Server-side validation
- Input sanitization
- Secure API endpoints
- Audit logs for all changes
- Ranks cannot be self-modified

### Performance

- Optimized images with next/image
- Code splitting and lazy loading
- Core Web Vitals optimized
- Mobile-first responsive design

### SEO

- Page-specific metadata
- Open Graph and Twitter metadata
- Sitemap and robots.txt
- Semantic HTML
- Schema markup

### Legal & Compliance

**Important Disclaimer:**
> "Rank qualification, rewards and benefits are subject to ServeCafe's official terms, verification process, eligibility requirements and applicable laws."

All reward percentages, rank requirements, and package prices are configurable through the admin dashboard.

### Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### License

This project is licensed under the MIT License.

### Support

For support, email support@servecafe.com or contact us through the website.

---

**ServeCafe** - Good Food. Great Community. Better Rewards.
