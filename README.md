# Keel

Will's personal operating system: today's one thing, an adaptive week, marriage and training logs, a morning journal, and a 90-day voyage.

- Static site served by GitHub Pages. No build step.
- Data lives in a private Supabase project (table `public.docs`, row-level security: each row readable and writable only by its owner).
- The publishable key in `index.html` is meant to be public; it grants nothing without a signed-in session.
