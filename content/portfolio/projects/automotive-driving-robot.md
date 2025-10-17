+++
date = '2025-10-08T17:37:30+08:00'
draft = false
title = 'Automotive Driving Robot'
+++

# Developing A Braking Robot Prototype For R&D In Fuel Efficiency & Autonomous Technology

#### Overview

The Automotive Driving Robot was my final-year group project during my Master’s in Mechanical Engineering (Automotive) at the University of Southampton, UK. It’s a mechatronic prototype built with a stepper motor, micro-LIDAR TOF sensor, and an Arduino-based PID control system, with key parts made using additive manufacturing. The system was tested in a Toyota Prius Plug-In Hybrid under a controlled, risk-assessed environment to validate its performance and safety.

---

#### Video

{{< youtube faJe8Imc2Zo >}}

We wanted a system that small research teams could actually use — not just admire from afar.  

Our design goals were straightforward:  

- 💰 **Affordable** enough for student or lab projects.  
- 🧠 **Driver-in-the-loop** — let a real person sit in the seat and brake naturally.  
- 🔧 **Flexible** — handle both straight-line and corner braking.  

The idea was to blend **robot precision** with **human feel**, so testing on real roads becomes safe and practical.  

---

## ⚙️ The Side-Force Trick  

Most robots push the pedal head-on with a linear actuator. We tried something different — we **pushed from the side**.  

This sideways actuation freed up legroom, made it easier for a driver to stay in the seat, and reduced the need for heavy frames. It’s a small shift, but it changes everything about how the system fits in the car.  

We built a prototype using recycled aluminium and 3D-printed parts — about 90% reused materials. It cost less than half our budget and still performed well in tests.  

---

## 📊 What We Found  

| Feature | AB Dynamics RBR 1500 | Our Prototype | Notes |
|----------|----------------------|----------------|-------|
| Max Force | 1600 N | ~500 N | Good for medium braking |
| Speed | 800–1600 mm/s | ~400 mm/s | Actuator-limited |
| Bandwidth | >10 Hz (est.) | ~3 Hz | Smooth response focus |
| Driver-in-the-Loop | ✅ | ✅ | Manual override included |
| Cost | £50,000+ | <£2,000 | Student-friendly budget |

> *Source: AB Dynamics RBR Series specifications.*  

Through **FEA in Ansys**, we stiffened the main bracket 14×, cutting pedal deflection from 14 mm to 1 mm under 500 N. The factor of safety went up by 50%. Not bad for something built from scrap.  

---

## 🌍 Why This Matters  

Affordable testing tools help more engineers explore **ADAS**, **regenerative braking**, and **autonomous driving**.  

Most small teams can’t afford high-end robots, so they skip the real data. We wanted to change that — to make meaningful research possible without million-dollar setups.  

When cost isn’t the bottleneck, creativity flows.  

---

## 🧭 What We Learnt  

We learnt that constraints force creativity.  

We made do with what we had — aluminium offcuts, 3D-printed joints, and a secondhand actuator. It wasn’t perfect, but it worked.  

A few key lessons:  

- Focus on *response speed*, not brute force.  
- Always include manual override. Safety first.  
- Don’t design in a vacuum — talk, test, tweak.  

We had delays, parts that didn’t fit, and sensors that failed, but every setback taught us something. The project became less about the robot, more about learning how to think and work like engineers.  

---

## 🚀 What’s Next  

The next step is adding **steering control** and better **force sensors** for feedback loops. We want full driver-in-the-loop control — braking, throttle, and steering — all tested safely.  

> “Good design doesn’t just solve problems. It opens doors for more people to build better things.”  

---

## 📸 Suggested Image Captions  

1. *Sketching the early side-force concept.*  
2. *FEA showing deflection before and after optimisation.*  
3. *Prototype installed in the Prius footwell.*  
4. *Driver-in-the-loop testing setup.*  
5. *Team running final actuation test.*  

---

## 🏁 Final Thoughts  

Engineering shouldn’t be locked behind a paywall.  

If you’re part of a research group or just an engineer with an idea, start small, test fast, and iterate. Innovation doesn’t come from big budgets — it comes from curiosity and grit.  

💬 *Got thoughts or similar projects? Drop a comment or connect on [LinkedIn](https://linkedin.com/).*  
