# TripWish

**Make a wish. We’ll plan the trip.**

TripWish is an AI travel-planning chatbot for iOS, currently in development. You describe a trip in plain language — for example, “4 days in Lisbon in May, foodie, mid-budget” — and TripWish turns that wish into a full plan: stays, flights, activities, and a day-by-day itinerary. When the plan looks right, one **Book it all** button books the whole trip.

Stays and travel bookings via Booking.com.

TripWish is an independent app. It is not operated or endorsed by Booking.com.

## Status

In development for iOS. Coming soon to the App Store. There is no public download yet, and this website does not sell or book travel.

## Features

- **Plain-language wishes.** A sentence is the brief: where, when, who it’s for, and the kind of trip.
- **A complete plan.** Stays, flights, activities, and a day-by-day itinerary in one place.
- **Bookable inventory.** Plans are built so they can be reserved. Stays and travel bookings via Booking.com.
- **Book it all.** One button books the trip you reviewed.
- **You decide.** Nothing is booked until you use that button.

## How it works

1. **Wish.** Type the trip the way you’d say it out loud.
2. **Plan.** TripWish builds the stays, flights, activities, and the shape of each day.
3. **Book in one tap.** Review the plan, then book the whole trip with **Book it all**.

## This website

The site in this repository is the promotional page for TripWish. It is static HTML and CSS, with a small vanilla script for the mobile menu. Fonts (Fraunces and Outfit, both SIL Open Font License) are self-hosted. There is no build step and no analytics.

From the repository root:

```bash
python3 -m http.server
```

Then open the local URL. Pages:

- `index.html` — landing page
- `privacy.html` — privacy policy

### Hosting

The site is hosted on **GitHub Pages** and published from the `main` branch.

**URL:** https://nikog8.github.io/tripwish/

[`.github/workflows/pages.yml`](.github/workflows/pages.yml) deploys the site on every push to `main`. The workflow uses `actions/configure-pages`, `actions/upload-pages-artifact`, and `actions/deploy-pages`.

Pages has to use **GitHub Actions** as the source (`build_type: workflow`). In the repository: **Settings → Pages → Build and deployment → Source: GitHub Actions**.

## Contact

[n3308371@gmail.com](mailto:n3308371@gmail.com)

Privacy policy: [privacy.html](privacy.html) · https://nikog8.github.io/tripwish/privacy.html
