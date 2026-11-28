<div align="center">

# Hi, I'm Akif Keklik 👋

Software Engineer · Backend Development · AI Engineering

[![LinkedIn](https://img.shields.io/badge/LinkedIn-akifkeklik-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/akifkeklik)
[![Medium](https://img.shields.io/badge/Medium-articles-000000?logo=medium&logoColor=white)](https://medium.com/@akifkeklik)
[![DEV.TO](https://img.shields.io/badge/DEV.TO-articles-0A0A0A?logo=devdotto&logoColor=white)](https://dev.to/akifkeklik)

</div>

I build complete products, backend to web, with tests and CI from the first commit. I care about financial
correctness, data isolation between users and tenants, and AI features that stay honest when the model is
unavailable.

**How I work:** no claim without a test, every change through a reviewed pull request, decisions written down.

| | |
|---|---|
| **Languages** | Java · Python · TypeScript · JavaScript |
| **Frameworks** | Spring Boot · Flask · Express · Next.js · Vue 3 |
| **Data and delivery** | PostgreSQL · MySQL · MongoDB · Supabase · Docker · GitHub Actions |

## Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/akifkeklik/jeweler-pro"><img src="https://raw.githubusercontent.com/akifkeklik/jeweler-pro/main/docs/images/dashboard.png" alt="Jeweler Pro dashboard" /></a>
      <h3><a href="https://github.com/akifkeklik/jeweler-pro">Jeweler Pro</a></h3>
      <p>Point of sale, stock and accounting for jewellery shops in Turkey.</p>
      <ul>
        <li>Gram pricing at live gold prices, <b>double-entry ledger</b>, one transaction per sale</li>
        <li>BigInt money math, tenant isolation on every query</li>
        <li><b>700+ tests</b>, end-to-end and accessibility checks on every pull request</li>
      </ul>
      <p><a href="https://jeweler-pro.vercel.app"><b>▶ Live demo</b></a> · Vue 3 · Express 5 · MongoDB</p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/akifkeklik/libris"><img src="https://raw.githubusercontent.com/akifkeklik/libris/main/docs/screenshots/home-desktop.png" alt="Libris home page" /></a>
      <h3><a href="https://github.com/akifkeklik/libris">Libris</a></h3>
      <p>Remember what you read: takeaways become AI recall questions, spaced review brings them back.</p>
      <ul>
        <li>Grounded AI answers from the catalogue (pgvector + Gemini), labelled fallback when offline</li>
        <li>Row-level security tested as two readers; Kindle, Readwise and Goodreads import</li>
        <li><b>1,300+ tests</b>, migrations validated on real PostgreSQL in CI</li>
      </ul>
      <p><a href="https://libris-pink.vercel.app"><b>▶ Live demo</b></a> · Next.js · Flask · Supabase</p>
    </td>
  </tr>
</table>

## More projects

| Project | What it does | Stack |
| --- | --- | --- |
| **[hospital-management-system](https://github.com/akifkeklik/hospital-management-system)** · [demo](https://hospital-management-system-rho-flax.vercel.app/) | Patient, doctor and admin workflows in eight languages: appointments, examinations, leave, AI department routing. [Postmortem of a production outage](https://medium.com/@akifkeklik/kod-de%C4%9Fi%C5%9Fmedi%C4%9Fi-halde-site-neden-%C3%A7%C3%B6kt%C3%BC-bir-hastane-randevu-sisteminden-ger%C3%A7ek-dersler-f712205ec386) | Java · Spring Boot · Next.js · MySQL |
| **[ecommerce-backend](https://github.com/akifkeklik/ecommerce-backend)** | Shop API: cart, discount codes, orders with row-locked stock, payments with refunds, moderated reviews; migrations validated on real PostgreSQL in CI | Java · Spring Boot · PostgreSQL · Flyway |
| **[weather-forecast-app](https://github.com/akifkeklik/weather-forecast-app)** | Current weather and a five-day forecast by city; server-side API key, caching and request coalescing | Next.js · TypeScript |
