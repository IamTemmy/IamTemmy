<table>
<tr>
<td width="58%" valign="middle">

<h1>Hi, I'm Temmy.</h1>

<strong>Electrical &amp; Computer Engineer</strong>

<br><br>
I build systems that <strong>sense the physical world, make decisions, and prove whether they worked.</strong>

<br><br>
<sub>hardware · embedded systems · sensing · autonomy · validation</sub>

</td>
<td width="42%" align="center" valign="middle">
<img src="assets/profile/signal-to-system.gif" alt="Signal evolving into circuit traces" width="390" />
</td>
</tr>
</table>

---

## Featured work

<table>
<tr>
<td width="33%" valign="top">
<a href="https://github.com/IamTemmy/plant-autonomy-testbed"><img src="assets/profile/plant-autonomy.png" alt="Plant Autonomy Testbed preview" width="100%" /></a>
<br><br>
<strong>01 / <a href="https://github.com/IamTemmy/plant-autonomy-testbed">Plant Autonomy Testbed</a></strong>
<br>
A closed-loop embedded system that senses soil, air, and light, controls watering and lighting, and verifies what happened through telemetry.
<br><br>
<sub>ESP32-WROVER · MQTT · Raspberry Pi · SQLite · Streamlit</sub>
</td>
<td width="33%" valign="top">
<a href="https://github.com/IamTemmy/trajectory-verification-system"><img src="assets/profile/trajectory-verification.png" alt="Trajectory Verification System preview" width="100%" /></a>
<br><br>
<strong>02 / <a href="https://github.com/IamTemmy/trajectory-verification-system">Trajectory Verification System</a></strong>
<br>
Verification tooling for autonomous-driving trajectories using map context, baselines, evaluation, and failure analysis on the Waymo Open Motion Dataset.
<br><br>
<sub>Python · NumPy · autonomy · evaluation</sub>
</td>
<td width="33%" valign="top">
<a href="https://github.com/IamTemmy/Oyster_gape"><img src="assets/profile/oyster-gape.png" alt="Oyster Gape Monitoring preview" width="100%" /></a>
<br><br>
<strong>03 / <a href="https://github.com/IamTemmy/Oyster_gape">Oyster Gape Monitoring</a></strong>
<br>
Non-contact Hall-effect sensing that turns oyster valve motion into calibrated physical gape measurements.
<br><br>
<sub>ESP32 · HAL 2425 · calibration &amp; linearization · Python</sub>
</td>
</tr>
</table>

---

## From the bench

> **Plant autonomy** — Traced a grow-light outage to a hard reboot from telemetry alone: an `uptime: 6s` reading after the MQTT last-will exposed the restart. Mitigation fixed; root cause still open.

> **Oyster gape** — Rebuilt calibration from measured constants: leadscrew reference at `0.001 mm/pulse`, feeding a 16-setpoint linearization.

> **Engineering principle** — Validation is not the last phase. If a system cannot tell you whether its action worked, the loop is incomplete.

---

## More work

**[pilotnet-reproduction](https://github.com/IamTemmy/pilotnet-reproduction)** — PyTorch reproduction of NVIDIA PilotNet: one camera frame → steering angle. `MAE 0.077`; `94.2%` of held-out predictions fall within ±0.20, with failure cases documented instead of hidden.

---

<sub>
Jackson, Mississippi · M.S. Electrical Engineering, Jackson State University · open to embedded / hardware / firmware / test opportunities
</sub>
