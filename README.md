# 👋 Hey, I'm Xiao Khan

**Flutter Developer • Backend Integrations • Real-Time Systems**

I build **production-ready mobile apps** and **scalable backends** with a strong focus on  
clean architecture, security, and real-time performance.

> I enjoy turning complex systems (payments, auth, MQTT, analytics)  
> into simple, reliable user experiences.

---

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
