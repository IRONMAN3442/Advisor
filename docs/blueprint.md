# **App Name**: ADvisor

## Core Features:

- ROI Projection: Generates projected ROI and revenue growth based on user-inputted data (budget, current revenue, ROI, campaign type) for demo users, using a generative AI tool. Includes a CTA after demo ROI projections: “Hire ADvisor to achieve this growth.”
- User Authentication: Secure user authentication with email/password and Google sign-in. Roles: admin, client, demo_user.
- Data Storage: Firestore database to store demo users, user profiles, campaign data, campaign metrics, and advisor insights. Track which demo users completed projection for follow-up.
- Admin Dashboard: Admin dashboard to manage users, campaigns, metrics, and advisor insights, with mobile-friendly design.
- Client Dashboard: Client dashboard to view campaigns, metrics, ROI, and advisor insights, with mobile-friendly design. Ensure DemoProjection and ClientDashboard are fully responsive.
- Campaign Insights: Display AI-generated insights, offering strategies to improve marketing campaign performance. Optionally show AI assumptions in a tooltip/modal. Builds trust with clients.
- Interactive Charts: Dynamic charts display campaign performance and ROI, offering admins and users the ability to view historic and current data with step-by-step windows to illustrate data. Placeholder for PDF/CSV export of charts and metrics.
- Notifications: Real-time alerts for admins: new demo users, underperforming campaigns, budget limits exceeded.

## Style Guidelines:

- Primary color: Vivid yellow (#FFCA28) for a clear visual relationship with Firebase
- Background color: Soft yellow (#FCF5E4), a desaturated version of the primary for a lighter feel.
- Accent color: Bright orange (#FF9800), for contrast and highlighting key actions and insights.
- Font pairing: 'Space Grotesk' (sans-serif) for headings and 'Inter' (sans-serif) for body text to convey modernity with approachability.
- Code font: 'Source Code Pro' (monospace) for any displayed code snippets or config details.
- Clean, modern icons to represent different metrics, campaigns, and insights.
- Step-by-step detail windows with images for an intuitive UX.