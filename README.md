<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=130&text=Xiao%20Khan&fontAlign=50&fontAlignY=40&color=gradient&animation=twinkling" />

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=26&pause=1000&color=00E5FF&center=true&vCenter=true&width=720&lines=Flutter+Developer;Backend+Integrations+%26+APIs;Real-time+Systems+%26+MQTT;Stripe+%2B+Supabase+Specialist;Clean+Architecture+Matters" />

<br/>

<img src="https://komarev.com/ghpvc/?username=xiaokhan&label=Profile%20Views&color=blueviolet&style=for-the-badge" />

</div>

---

## 🧠 About Me

```txt
I build systems that:
✔ scale predictably
✔ handle payments securely
✔ survive real-world edge cases
✔ stay readable after 6 months


## 🧠 What I Work With

### 📱 Mobile
- Flutter (production apps)
- Riverpod / GetX (migration & refactors)
- Clean Architecture
- Firebase Analytics & Auth

### 🔌 Backend & APIs
- REST APIs (Node / Dart)
- Supabase (Edge Functions, Auth, DB)
- Stripe (Payment Intents, Webhooks)
- Secure token handling

### ⚡ Real-Time Systems
- MQTT (IoT-style messaging)
- WebSockets
- Live dashboards & device state sync

### 🛠️ Other Tools
- Git & GitHub
- Linux (daily driver)
- Firebase
- Docker (basic)

---

## 🚀 Things I Care About

- 🧩 **Architecture over hacks**
- 🔐 **Security-first APIs**
- 📉 **Reducing state & complexity**
- 📡 **Reliable real-time data**
- 🧼 **Readable, boring, maintainable code**

---

## 🧪 Current Interests

- Migrating large Flutter apps (GetX → Riverpod)
- Stripe + Supabase payment flows
- Token lifecycle & auth edge cases
- MQTT reconnect strategies
- Analytics that actually matter

---

## 📌 Example: Real-World Focus

```dart
// Example: Safer API call pattern with token refresh
final response = await dio.get(
  '/start-ride',
  options: Options(
    headers: {
      'Authorization': 'Bearer $accessToken',
    },
  ),
);

// Handle 401 → refresh → retry cleanly
