# salonexemple 🇩🇪 README (Deutsch)
Beautysalon Harmonie – Moderne Website für lokalen Salon

Dies ist eine vollständig entwickelte, statische und suchmaschinenoptimierte Website für den Beautysalon Harmonie in Hannover.
Die Seite wurde mit Fokus auf Design, Performance, DSGVO-Konformität und lokale SEO erstellt.

🌐 Live-Version

https://bsalon.vercel.app

🛠️ Technologien
Frontend

HTML5 / CSS3

TailwindCSS (CDN-Version)

Vanilla JavaScript
Für Navigation, Smooth Scrolling, Mobile Menu, Cookie Banner und Form-Handling.

Hosting

Vercel (statische Bereitstellung)

Datenbank & Backend

Supabase

Speicherung von Terminanfragen in der Tabelle appointments

Edge Function zum Versenden von E-Mails an den Salon (send-booking-email)

DSGVO & Cookies

Benutzerdefinierter Cookie Consent Manager:

Consent Mode v2 kompatibel

Analytics / Marketing / Preferences ein- und ausschaltbar

Vollständig ohne externe Libraries

Modal + Banner + focus trapping + Keyboard-Navigation

Analytics (optional)

Google Analytics 4 (Consent-abhängig geladen)

Consent Mode v2 integriert

🎨 Design & UI

Luxuriöses Premium-Design mit goldenen Akzenten

Hero-Section mit Gradient-Background

Animierte Scroll-Navigation

Responsive Layout (Mobile, Tablet, Desktop)

Moderne Service-Karten und Preistabellen

Testimonials, Galerie, Google Maps Integration

WhatsApp Floating Button für hohe Conversion

🔍 SEO Features

Vollständige Meta-Tags (title, description, keywords, robots)

Open Graph / Social Media Vorschau

canonical-Link

Strukturierte Daten (Schema.org / BeautySalon)

ALTs für alle Bilder

Sitemap & Robots optional integrierbar

Performance-Optimierungen (lazy loading, optimierte images)

📬 Kontaktformular

Das Kontaktformular speichert:

Name

E-Mail

Telefon

Gewünschte Leistung

Nachricht

Ursprungsseite

Automatischer Prozess:

Formulardaten → Supabase appointments

Supabase Edge Function sendet E-Mail an den Salon

Nutzer erhält Statusmeldung auf der Seite

📁 Projektstruktur (vereinfacht)
/images
   /gallery
   salon.jpg
index.html
datenschutz.html
impressum.html
agb.html
favicon.ico
manifest.json


Alle Styles befinden sich innerhalb von <style> im Header (monolithisches Setup).

🚀 Deployment

Projekt auf GitHub pushen

Auf Vercel importieren

Build Target: Static

Domain hinzufügen (optional)

👤 Entwickler

Projekt erstellt von Maxim 
Full-Stack Developer & Web3 Builder



🇬🇧 README (English)
Beautysalon Harmonie – Modern Website for a Local Beauty Salon

This is a fully developed static website built for Beautysalon Harmonie in Hannover.
The project focuses on design, performance, GDPR compliance, and local SEO visibility.

🌐 Live Version

https://bsalon.vercel.app

🛠️ Technologies
Frontend

HTML5 / CSS3

TailwindCSS (CDN version)

Vanilla JavaScript
Used for navigation, smooth scrolling, mobile menu, cookie banner, and form handling.

Hosting

Vercel (static hosting)

Database & Backend

Supabase

Stores booking requests inside the appointments table

Edge Function for sending booking emails (send-booking-email)

GDPR & Cookies

Custom Cookie Consent Manager:

Consent Mode v2 ready

Analytics / marketing / preference toggles

Fully custom implementation (no libraries)

Modal system with keyboard support and focus trapping

Analytics (optional)

Google Analytics 4 (loaded only with consent)

Consent Mode v2 included

🎨 Design & UI

Luxury premium design with gold accents

Gradient hero section

Smooth scroll navigation

Responsive layout for all devices

Modern service cards and pricing tables

Testimonials, gallery, and Google Maps integration

WhatsApp floating button for conversions

🔍 SEO Features

Full meta tags (title, description, keywords, robots)

Open Graph for social media preview

Canonical link

Structured data (Schema.org / BeautySalon)

ALT tags on all images

Lazy loading for better performance

Sitemap & Robots.txt supported

📬 Contact Form

The booking form collects:

Name

Email

Phone number

Selected service

Message

Source page (URL)

Automated pipeline:

Submit form → Supabase appointments

Supabase Edge Function sends confirmation email to the salon

The user receives a success message on the site

📁 Project Structure (simplified)
/images
   /gallery
   salon.jpg
index.html
datenschutz.html
impressum.html
agb.html
favicon.ico
manifest.json


All styling is embedded inside <style> (monolithic structure).

🚀 Deployment

Push repo to GitHub

Import project to Vercel

Set build target to Static

Add custom domain (optional)

👤 Developer

Project built by Maxim
Full-Stack Developer & Web3 Builder