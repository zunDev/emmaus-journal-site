# 엠마오 저널 개인정보처리방침

시행일: 2026년 11월 24일

엠마오 저널(이하 ‘앱’)은 zunDev(이하 ‘운영자’)가 만든 개인 일기 앱입니다. 이 방침은 iPhone용과 Android용 앱 모두에 적용됩니다.

## 한눈에 보기

- 운영자는 이용자의 개인정보를 수집하지 않습니다.
- 회원 가입이 없고, 앱은 인터넷에 연결하지 않습니다.
- 일기는 이용자의 기기 안에만 저장됩니다. 운영자는 일기를 볼 수 없습니다.
- 광고나 분석 도구, 외부 업체의 추적 기능을 쓰지 않습니다.

## 1. 수집하는 개인정보

운영자는 어떤 개인정보도 수집하거나 전송받지 않습니다. 앱에는 서버와 통신하는 기능이 없습니다.

## 2. 기기 안에 저장되는 정보

앱이 동작하려면 다음 정보를 이용자의 기기 안에 저장합니다. 이 정보는 기기 밖으로 보내지 않습니다.

| 항목 | 내용 | 보관 기간 |
| --- | --- | --- |
| 일기 | 날짜, 그날의 질문, 본문, 마지막 수정 시각 | 이용자가 삭제할 때까지 |
| 휴지통 | 지운 일기와 지운 시각 | 지운 날부터 30일. 그 뒤 앱을 열 때 자동으로 영구 삭제 |
| 앱 설정 | 알림 사용 여부와 시각, 첫 안내를 본 여부 | 이용자가 앱을 삭제할 때까지 |

일기와 휴지통은 앱 전용 저장 공간에 보관합니다. 운영체제의 자동 백업(iCloud 백업, Android 자동 백업)에는 포함하지 않도록 설정했습니다. 그래서 기기를 바꾸면 일기가 자동으로 옮겨지지 않습니다. 옮기려면 아래의 암호화 백업을 사용하세요.

## 3. 암호화 백업 파일

이용자가 **설정 → 암호화 백업**을 실행하면, 이용자가 정한 암호로 일기를 암호화한 파일을 만듭니다. 암호에서 PBKDF2-HMAC-SHA256으로 키를 만들고, 그 키로 AES-256-GCM 암호화를 합니다.

- 파일을 어디에 저장할지는 이용자가 고릅니다. iCloud Drive, Google Drive 같은 저장소를 고르면 해당 서비스의 개인정보처리방침이 적용됩니다.
- 암호는 기기에 저장하지 않고 운영자에게도 전달되지 않습니다. 암호를 잊으면 운영자도 파일을 복원할 수 없습니다.
- 휴지통에 있는 일기는 백업 파일에 들어가지 않습니다.

## 4. 알림

이용자가 알림을 켜면 기기 안에서 매일 정한 시각에 알림을 예약합니다. 알림을 켤 때 운영체제가 권한을 묻습니다. 잠금 화면에는 “하루를 돌아볼 시간이에요.”라는 문구만 보이고, 일기 내용은 보이지 않습니다. 알림은 서버를 거치지 않습니다.

## 5. 제3자 제공과 처리 위탁

운영자는 이용자의 정보를 제3자에게 제공하거나 처리를 위탁하지 않습니다. 앱에는 외부 업체의 광고, 분석, 추적 도구가 들어 있지 않습니다.

App Store와 Google Play는 이용자가 기기 설정에서 동의한 경우 앱의 오류 보고와 사용 통계를 수집해 개발자에게 익명 통계로 보여 줄 수 있습니다. 이 정보는 Apple과 Google이 각자의 방침에 따라 처리하며, 일기 내용은 포함되지 않습니다.

## 6. 정보의 삭제

- 앱에서 일기를 지우면 휴지통으로 옮겨지고, 30일 뒤 또는 이용자가 **영구 삭제**나 **비우기**를 누를 때 기기에서 지워집니다.
- 앱을 삭제하면 기기 안의 일기, 휴지통, 설정이 모두 지워집니다. 이용자가 따로 저장한 백업 파일은 이용자가 직접 지워야 합니다.

운영자는 이용자의 정보를 갖고 있지 않으므로 열람, 정정, 삭제를 대신 처리할 정보가 없습니다. 이용자는 앱 안에서 언제든 직접 읽고 고치고 지울 수 있습니다.

## 7. 어린이

앱은 만 14세 미만 어린이를 대상으로 하지 않으며, 어린이의 개인정보도 수집하지 않습니다.

## 8. 안전을 위한 조치

일기는 기기의 앱 전용 저장 공간에 두어 다른 앱이 읽지 못하게 합니다. 백업 파일은 이용자의 암호로 암호화하고, 파일이 바뀌면 복원하지 않습니다. 기기 자체의 잠금(암호, Face ID, 지문 등)을 켜 두시길 권합니다.

## 9. 문의

개인정보와 관련한 문의는 아래로 보내 주세요.

- 운영자: zunDev
- 이메일: emmaus@zundev.dev

## 10. 방침의 변경

이 방침이 바뀌면 앱 업데이트 안내와 이 페이지에 시행일과 함께 알립니다. 수집하는 정보가 생기는 변경이라면 시행 전에 앱 안에서 먼저 알립니다.

---

# Emmaus Journal Privacy Policy

Effective: November 24, 2026

Emmaus Journal (“the app”) is a personal journaling app made by zunDev (“we”). This policy covers both the iPhone and Android apps.

## Summary

- We do not collect any personal information.
- There is no sign-up, and the app does not connect to the internet.
- Your journal stays on your device. We cannot see it.
- The app contains no advertising, analytics or third-party tracking.

## 1. Information we collect

None. The app has no feature that communicates with a server.

## 2. Information stored on your device

To work, the app stores the following on your device only. It is never sent off the device.

| Item | What it contains | How long it is kept |
| --- | --- | --- |
| Journal entries | Date, the day’s question, your text, last edited time | Until you delete them |
| Trash | Deleted entries and when they were deleted | 30 days from deletion, then removed the next time the app opens |
| Settings | Whether reminders are on and their time, whether you have seen the welcome guide | Until you delete the app |

Entries and trash are kept in the app’s private storage and are excluded from the operating system’s automatic backups (iCloud Backup, Android Auto Backup). They do not move to a new phone automatically; use an encrypted backup for that.

## 3. Encrypted backup files

When you choose **Settings → Encrypted backup**, the app creates a file encrypted with a password you choose. The key is derived from your password with PBKDF2-HMAC-SHA256, and the file is encrypted with AES-256-GCM.

- You choose where the file is saved. If you choose a service such as iCloud Drive or Google Drive, that service’s privacy policy applies.
- Your password is never stored or sent to us. If you forget it, we cannot recover the file.
- Entries in the trash are not included in backups.

## 4. Reminders

If you turn reminders on, the app schedules a daily notification on your device, and your operating system asks for permission first. The lock screen shows only “하루를 돌아볼 시간이에요.” (“Time to look back on your day.”), never your journal text. Reminders do not go through any server.

## 5. Sharing with third parties

We do not share your information with anyone or use any processors. The app contains no third-party advertising, analytics or tracking code.

If you have agreed in your device settings, Apple and Google may collect crash reports and usage statistics and show them to developers as anonymous totals. They handle this under their own policies, and it never includes your journal text.

## 6. Deleting your information

- Deleting an entry moves it to the trash. It is erased from the device after 30 days, or when you tap **Delete forever** or **Empty**.
- Deleting the app erases all entries, the trash and settings from the device. Backup files you saved elsewhere must be deleted by you.

Because we hold none of your information, there is nothing for us to access, correct or delete on your behalf. You can read, edit and delete everything yourself in the app at any time.

## 7. Children

The app is not directed at children under 14 and collects no information from children.

## 8. Security

Entries are kept in the app’s private storage, which other apps cannot read. Backup files are encrypted with your password and are rejected on restore if they have been altered. We recommend turning on your device’s own lock (passcode, Face ID or fingerprint).

## 9. Contact

- Operator: zunDev
- Email: emmaus@zundev.dev

## 10. Changes to this policy

If this policy changes, we will post the new version here with its effective date and mention it in the app update notes. If a change would mean collecting any information, we will tell you in the app before it takes effect.
