<div align="center">

# Vũ Quang Anh
### `AI · Security · Dev · BA`

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&pause=1200&color=A3E635&center=true&vCenter=true&width=650&lines=I+build+systems%2C+learn+the+business+behind+them...;...then+try+to+break+them+before+someone+else+does.;Multi-stack+backend+%E2%86%92+Web+Pentesting+%26+Security;Final-year+Software+Engineering+Student+%40+HOU" alt="Typing Tagline" />
</a>

<br/>

<p align="center">
  <a href="https://vuquanganh.vercel.app/"><img src="https://img.shields.io/badge/Live_Portfolio-vuquanganh.vercel.app-A3E635?style=for-the-badge&logo=vercel&logoColor=black" alt="Portfolio" /></a>
  <a href="mailto:vuquanganhnd2005@gmail.com"><img src="https://img.shields.io/badge/Email-vuquanganhnd2005@gmail.com-18181B?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/AnhQuangVu"><img src="https://img.shields.io/badge/GitHub-AnhQuangVu-18181B?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

</div>

---

### `01 // About`

> *"Multi-stack backend background, heading toward penetration testing and bug bounty. I use business understanding to find logic flaws, and AI to automate the repetitive parts."*

- 🎓 **Học vấn:** Sinh viên năm cuối ngành Kỹ thuật Phần mềm — **Đại học Mở Hà Nội (Hanoi Open University)**.
- 💼 **Kinh nghiệm:** Cựu Thực tập sinh Phát triển Phần mềm & An toàn thông tin tại **Trung tâm Công nghệ Thông tin (Digital Technology Center — HOU)**:
  - Vận hành & phát triển các hệ thống trường đại học: Thư viện số, Tạp chí khoa học.
  - Thực hiện pentest có ủy quyền trên các ứng dụng web nội bộ và đề xuất bản vá bảo mật.
- 📍 **Địa điểm:** Hà Nội, Việt Nam.

---

### `02 // Four Areas · One Way of Working`

```
┌──────────────┬─────────────────────────────────────────────────────────────────────────────┐
│ 01 — AI      │ Applied AI: Tích hợp LLM vào luồng nghiệp vụ thực (recommendation, matching,│
│              │ rule-based fallback, human-in-the-loop). Python, FastAPI, Playwright.       │
├──────────────┼─────────────────────────────────────────────────────────────────────────────┤
│ 02 — SEC     │ Security: Zero-trust architecture (OIDC/PKCE Keycloak, APISIX edge token    │
│              │ validation, RBAC + Row Level Security), SHA-256 audit ledger, Web pentest.  │
├──────────────┼─────────────────────────────────────────────────────────────────────────────┤
│ 03 — DEV     │ Development: Backend Java 21 / Spring Boot, ASP.NET Core, FastAPI;          │
│              │ Event-driven (Kafka, MQTT); Ràng buộc toàn vẹn CSDL; Shipped via Docker/CI. │
├──────────────┼─────────────────────────────────────────────────────────────────────────────┤
│ 04 — BA      │ Business Analysis: Mô hình hóa tác nhân & phân quyền, BPMN 2.0 (Flowable), │
│              │ Thiết kế vòng đời trạng thái, đặc tả quy tắc nghiệp vụ & nghiệm thu.       │
└──────────────┴─────────────────────────────────────────────────────────────────────────────┘
```

---

### `03 // Selected Projects`

#### 🌊 [FloodOS](https://github.com/AnhQuangVu) *(2026)* — `BA · SEC · DEV · AI`
*Hệ điều hành mã nguồn mở điều phối ứng phó ngập lụt đô thị Hà Nội — Đề tài tham dự Olympic Phần mềm nguồn mở Việt Nam 2026 (DX-OS Open-Core track).*
- **BA & BPMN 2.0:** Mô hình hóa 5 vai trò tác nhân; 2 luồng quy trình nghiệp vụ chuẩn BPMN thực thi trên **Flowable** (SOP-01 điều phối cứu trợ, SOP-02 sự cố phương tiện); thiết kế thang điểm cứu hộ 100 điểm & vòng đời 7 trạng thái.
- **Zero-Trust Security:** SSO OIDC/PKCE qua **Keycloak**; xác thực token tại **Apache APISIX** edge gateway; phân quyền 2 lớp (RBAC + Row Level Security); quét mã độc ClamAV và nhật ký kiểm toán SHA-256 chống giả mạo.
- **Architecture & Backend:** Lõi hướng sự kiện 3 tầng qua **Kafka** và **MQTT**; **Java 21**, **PostgreSQL 16** (ràng buộc ngăn trùng lịch phương tiện); bản đồ vận hành thời gian thực với **React 19 + MapLibre GL**.
- **AI Assistant & DevOps:** Trợ lý **FastAPI** gợi ý thứ tự ưu tiên với sự phê duyệt của con người & cơ chế fallback; 429 automated tests, đóng gói container hoàn chỉnh với **Docker Compose**.

#### 🚀 [StartUp Kit](https://github.com/AnhQuangVu/Startup-Kit-BE) *(2025 — 2026)* — `BA · AI · DEV`
*Nền tảng kết nối hai chiều (Two-sided Marketplace) giữa Startups, Mentors và Nhà đầu tư.*
- **Chuyển đổi mô hình:** Tái định hình từ mô hình vườn ươm cố định sang thị trường kết nối theo nhu cầu; cấu trúc 4 đơn vị vận hành và đa dạng dòng doanh thu.
- **DFD & Đặc tả nghiệp vụ:** Định nghĩa 5 vai trò tác nhân gắn liền sơ đồ DFD; chuẩn hóa 6 quy trình nghiệp vụ cốt lõi kèm tiêu chí nghiệm thu rõ ràng.
- **Tích hợp AI & Backend:** Tính năng AI tạo hồ sơ, gợi ý mentor và khớp nối nhà đầu tư; RESTful APIs với **Spring Boot (Java)**, **Spring Security & JWT**, **PostgreSQL**, **Next.js** và **Docker**.

---

### `04 // Tech Stack & Tooling`

<div align="center">

| Lĩnh vực | Công nghệ / Công cụ chính |
| :--- | :--- |
| **Phân tích nghiệp vụ (BA)** | BPMN 2.0 (Flowable) · DFD · Phân tích tác nhân & phân quyền · Vòng đời trạng thái · Kịch bản nghiệm thu |
| **An toàn thông tin (SEC)** | OIDC / PKCE (Keycloak) · Apache APISIX Gateway · RBAC + PostgreSQL RLS · Web Pentesting (IDOR, Lỗi logic) · SHA-256 Audit · Burp Suite · OWASP Top 10 |
| **Backend & Hệ thống** | Java 21 · Spring Boot · FastAPI · ASP.NET Core · PostgreSQL 16 · Apache Kafka · MQTT |
| **Trí tuệ nhân tạo (AI)** | LLM Integration (OpenAI, Gemini) · Rule-based Fallback · Human-in-the-loop · Prompt Engineering · Playwright |
| **Giao diện & DevOps** | React 19 · Next.js · TypeScript · Docker & Compose · GitHub Actions (CI/CD) · Nginx · Linux VPS |

</div>

---

### `05 // GitHub Activity`

<div align="center">
  <img height="155em" src="https://github-readme-stats-sigma-five.vercel.app/api?username=AnhQuangVu&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&bg_color=0D1117&title_color=A3E635&icon_color=A3E635&text_color=94A3B8" alt="GitHub Stats" />
  <img height="155em" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=AnhQuangVu&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A3E635&text_color=94A3B8" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=AnhQuangVu&theme=tokyonight&hide_border=true&background=0D1117&ring=A3E635&fire=A3E635&currStreakLabel=A3E635" alt="GitHub Streak" />
</div>

---

<div align="center">
  <p><i>"Have a problem to solve? Let's make software harder to break. Always open to discuss system architecture, application security challenges, or new collaboration opportunities."</i></p>
  <sub>🌐 <a href="https://vuquanganh.vercel.app/">vuquanganh.vercel.app</a> &nbsp;•&nbsp; ✉️ <a href="mailto:vuquanganhnd2005@gmail.com">vuquanganhnd2005@gmail.com</a> &nbsp;•&nbsp; 📍 Hanoi, Vietnam</sub>
</div>
