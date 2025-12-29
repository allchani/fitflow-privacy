---
title: "개인정보처리방침 — 틈새스쿼트 (영문명: EasySquat)"
---

## 📌 개인정보처리방침 — 틈새스쿼트 (영문명: EasySquat)

**최종 업데이트: 2025-12-29**

본 애플리케이션(**“틈새스쿼트”**, 영문명 **“EasySquat”**, 이하 “본 앱”)은 서비스 제공 및 계정 관리를 위해 사용자의 데이터를 **직접 수집하고 FireStore 서버에 저장**합니다. 본 앱이 수집하는 주요 데이터는 **구글 계정을 통한 사용자 식별 정보(이메일 주소, 사용자 ID, 이름)** 및 **사용자가 직접 기록한 운동 데이터(피트니스 정보)**입니다.

또한, 본 앱은 Google AdMob(광고), Google User Messaging Platform(UMP) 및 Firebase(Analytics, Crashlytics)를 이용하는 과정에서 Google이 광고 제공, 성능 분석 및 앱 안정성 유지를 위해 일부 데이터를 자동으로 수집할 수 있습니다.

본 앱 개발자는 수집된 사용자 ID, 이름 및 운동 기록을 **서비스 운영, 랭킹 제공 및 개선을 목적으로 직접 관리**합니다.

---

### 1. 앱이 직접 수집·저장하는 데이터

본 앱은 서비스 제공, 계정 관리 및 랭킹 시스템 운영을 위해 다음 데이터를 **직접 수집하고 FireStore 서버에 저장**합니다.

| 데이터 유형 | 수집 목적 | 보관 기간 |
| :--- | :--- | :--- |
| **개인 식별 정보** | 구글 로그인 시 연동되는 **이메일 주소, 사용자 고유 ID** | 계정 삭제 시까지 보관 |
| **프로필 정보** | 랭킹 시스템 및 사용자 식별을 위한 **이름(닉네임)** | 계정 삭제 시까지 보관 |
| **피트니스 정보** | 사용자가 기록한 **스쿼트 횟수, 세트 등** 모든 운동 기록 | 계정 삭제 시까지 보관 |

---

### 2. 제3자(Google) SDK에 의해 자동 수집될 수 있는 데이터

본 앱은 서비스 운영, 분석, 광고 제공을 위해 Google의 다양한 서비스(AdMob, Firebase Analytics, Crashlytics)를 사용하며, Google은 다음과 같은 정보를 **자동으로 수집 및 처리**할 수 있습니다.

| 데이터 유형 | 수집 목적 |
| :--- | :--- |
| **기기 식별자** (예: Google AD_ID) | 광고 제공, 광고 성능 분석 및 사용자 분석 (애널리틱스) |
| **앱 상호작용 및 활동** | 앱 사용 패턴, 클릭, 세션 정보 등 (앱 기능 개선 및 애널리틱스 목적) |
| **앱 안정성 및 성능** | 비정상 종료 로그, 진단 데이터 (앱 성능 및 안정성 유지 목적) |

⚠ 본 앱 개발자는 앱 활동 데이터 및 안정성 데이터는 **앱 성능 분석 및 개선을 목적**으로 열람 및 사용합니다. 광고 관련 데이터는 직접 접근하거나 관리하지 않습니다.

Google의 데이터 수집 정책은 다음에서 확인할 수 있습니다:
https://policies.google.com/technologies/ads

---

### 3. 광고 및 동의 관리 (Google UMP)

본 앱은 Google UMP를 사용하여 사용자의 광고 개인화 동의 여부를 확인 및 관리합니다. 사용자는 광고 개인화 허용/거부를 선택할 수 있으며, 거부한 경우 비개인화 광고(NPA)가 표시됩니다. 동의 선택은 언제든지 앱 내 설정에서 변경할 수 있습니다.

---

### 4. 데이터 보관·삭제

본 앱 개발자는 수집된 사용자 계정 정보(이메일, ID, 이름) 및 모든 스쿼트 기록을 **FireStore 서버에 보관**합니다.

* **보관 기간:** 데이터는 사용자가 계정을 삭제할 때까지 보관됩니다.
* **삭제 절차:** 사용자는 **앱 내 설정**을 통해 또는 다음 **계정 삭제 요청 링크**를 통해 계정 및 모든 관련 데이터의 삭제를 요청할 수 있습니다.
    * **계정 삭제 요청 링크:** **https://forms.gle/tXK5bPNrf8KZ6qCFA**
* **보존 데이터:** 법적 또는 회계상의 의무 이행을 위해 일부 필수 정보(예: 이용 약관 동의 기록)는 최대 1년 동안 보존될 수 있습니다.

---

### 5. 국제 데이터 전송

본 앱은 FireStore 서버를 사용하며, Google AdMob/UMP 및 Firebase는 글로벌 서비스로서 데이터가 사용자의 거주 국가 외의 서버에서 처리될 수 있습니다. 이 전송은 Google의 개인정보처리방침에 따라 관리됩니다.

---

### 6. 권한 사용 목적

본 앱은 아래의 권한을 앱 기능 제공 목적에 한해 사용합니다:

* **전화 상태 권한 (READ_PHONE_STATE):** 운동 재생 중 전화가 걸리면 자동으로 운동을 일시정지하기 위해 필요합니다. 어떠한 정보도 외부로 전송되지 않습니다.
* **다른 앱 위에 그리기 권한 (SYSTEM_ALERT_WINDOW):** 사용자가 다른 앱을 사용하는 동안에도 플로팅 타이머나 운동 현황을 화면에 표시하기 위해 사용됩니다.

---

### 7. 개인정보 문의

문의: km.fitflow@gmail.com

---

### 8. 본 방침의 변경

본 정책은 기능 추가 또는 Google 정책 변경에 따라 업데이트될 수 있습니다. 중요한 변경이 있을 경우 앱 내 공지 또는 본 페이지 갱신을 통해 안내합니다.

<br>
<br>

## 📌 Privacy Policy — EasySquat (English)

**Last updated: 2025-12-29**

**EasySquat** (“the App”) **directly collects and stores** user data on the **FireStore server** for the purpose of service provision and account management. The key data collected includes **user identification information (Email address, User ID, Name) via Google Sign-In** and **user-recorded workout data (Fitness Information)**.

Additionally, the App uses Google AdMob (ads), the Google User Messaging Platform (UMP), and Firebase (Analytics, Stability). Google may automatically collect certain information for ad serving, performance analytics, and app stability.

The App developer directly manages and accesses the collected User IDs, Names, and workout records solely for the purpose of operating and improving the service and providing ranking features.

---

### 1. Data the App Collects Directly

The App directly collects and stores the following data on the FireStore server for service provision, account management, and ranking systems:

| Data Type | Purpose of Collection | Retention Period |
| :--- | :--- | :--- |
| **Personal Identifiers** | **Email address, User ID** obtained via Google Sign-In. | Retained until account deletion. |
| **Profile Information** | **Name (Nickname)** for ranking system and user identification. | Retained until account deletion. |
| **Fitness Information** | All workout data, including **squat counts, and sets** recorded by the user. | Retained until account deletion. |

---

### 2. Data Automatically Collected by Third-Party Services

Through Google AdMob, UMP, and Firebase, Google may collect:

| Data Type | Purpose of Collection |
| :--- | :--- |
| **Device Identifiers** (e.g., Google AD_ID) | Ad serving, ad performance analytics, and user analytics. |
| **App Interactions and Activity** | App usage patterns, clicks, session information (App improvement and Analytics purposes). |
| **App Stability and Performance** | Crash logs, diagnostics (App performance and stability maintenance). |

The App developer accesses and uses the App Activity and Stability data solely for the purpose of analyzing and improving the App's performance and stability.

Google Privacy Policy:
https://policies.google.com/technologies/ads

---

### 3. Ads & Consent (Google UMP)

UMP is used to request and manage the user’s ad consent. Users may allow or decline personalized ads. If declined, non-personalized ads (NPA) are served. Users may update consent preferences within the App when available.

---

### 4. Data Retention & Deletion

The App developer retains the collected **user account information (email, ID, name) and all squat records on the FireStore server.**

* **Retention Period:** Data is retained until the user deletes their account.
* **Deletion Procedure:** Users may request the deletion of their account and all associated data through the in-app settings or via the following **Account Deletion Request Link:**
    * **Account Deletion Link:** **https://forms.gle/tXK5bPNrf8KZ6qCFA**
* **Retention Data:** Some minimal data (e.g., TOS acceptance records) may be retained for up to 1 year for legal or accounting compliance.

---

### 5. International Data Transfers

Data may be processed on servers located in various countries as Google AdMob/UMP and Firebase are global services.

---

### 6. Permissions Used

The App uses the following permissions solely for the purpose of providing App features:

* **Phone State (READ_PHONE_STATE):** Used to pause workouts automatically during incoming calls. No data is transmitted externally.
* **Display Over Other Apps (SYSTEM_ALERT_WINDOW):** Used to display a floating timer or workout status on the screen while the user is using other apps.

---

### 7. Contact

Email: km.fitflow@gmail.com

---

### 8. Changes to This Policy

We may update this policy as features evolve or policies change. Major updates will be announced in-app and on this page.
