<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Privacy Policy — Orbit</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background-color: #000000;
      color: #ffffff;
      font-family: -apple-system, BlinkMacSystemFont, 
        'Segoe UI', Roboto, sans-serif;
      font-size: 16px;
      line-height: 1.7;
      padding: 0 20px;
    }

    .container {
      max-width: 720px;
      margin: 0 auto;
      padding: 60px 0;
    }

    .header {
      margin-bottom: 48px;
      padding-bottom: 32px;
      border-bottom: 1px solid #1F2937;
    }

    .logo {
      font-size: 20px;
      font-weight: 700;
      color: #ffffff;
      margin-bottom: 32px;
      display: block;
    }

    h1 {
      font-size: 36px;
      font-weight: 700;
      color: #ffffff;
      margin-bottom: 8px;
      line-height: 1.2;
    }

    .last-updated {
      color: #6B7280;
      font-size: 14px;
      margin-top: 8px;
    }

    h2 {
      font-size: 20px;
      font-weight: 600;
      color: #ffffff;
      margin-top: 40px;
      margin-bottom: 16px;
    }

    p {
      color: #D1D5DB;
      margin-bottom: 16px;
    }

    ul {
      color: #D1D5DB;
      padding-left: 20px;
      margin-bottom: 16px;
    }

    ul li {
      margin-bottom: 8px;
    }

    .section {
      padding: 32px 0;
      border-bottom: 1px solid #111111;
    }

    .section:last-child {
      border-bottom: none;
    }

    .highlight-box {
      background: #111111;
      border: 1px solid #1F2937;
      border-radius: 12px;
      padding: 20px 24px;
      margin: 24px 0;
    }

    .highlight-box p {
      margin-bottom: 0;
      color: #9CA3AF;
      font-size: 14px;
    }

    .not-collected {
      color: #6B7280;
    }

    .not-collected li {
      color: #6B7280;
    }

    .footer {
      margin-top: 60px;
      padding-top: 32px;
      border-top: 1px solid #1F2937;
      color: #6B7280;
      font-size: 14px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      gap: 12px;
    }

    .footer a {
      color: #3B82F6;
      text-decoration: none;
    }

    .footer a:hover {
      text-decoration: underline;
    }

    a {
      color: #3B82F6;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    @media (max-width: 640px) {
      h1 {
        font-size: 28px;
      }
      .container {
        padding: 40px 0;
      }
      .footer {
        flex-direction: column;
        align-items: flex-start;
      }
    }
  </style>
</head>
<body>
  <div class="container">

    <div class="header">
      <span class="logo">Orbit</span>
      <h1>Privacy Policy</h1>
      <p class="last-updated">Last updated: July 31, 2026</p>
    </div>

    <div class="section">
      <p>
        Orbit ("we", "our", or "us") is a UPI money 
        tracking app for Android. This policy explains 
        what data we collect, how we use it, and your 
        rights over it.
      </p>
    </div>

    <div class="section">
      <h2>1. What We Collect</h2>
      <p>
        We collect only what is necessary to provide 
        the service:
      </p>
      <ul>
        <li>Your name and email address (via Google 
          Sign-In, entered by you)</li>
        <li>Transaction data: merchant name, amount, 
          date, and category</li>
        <li>App preferences and settings</li>
        <li>Device token for push notifications 
          (EMI and recurring charge reminders only)</li>
      </ul>

      <p>We do not collect:</p>
      <ul class="not-collected">
        <li>Raw SMS message content</li>
        <li>OTPs or authentication codes</li>
        <li>Personal or non-financial messages</li>
        <li>Bank account numbers or card numbers</li>
        <li>Location data</li>
        <li>Gmail messages or email content</li>
        <li>Any data not directly related to your 
          financial transactions</li>
      </ul>
    </div>

    <div class="section">
      <h2>2. SMS Permission</h2>
      <p>
        Orbit requests permission to read SMS messages 
        on your device. This permission is used 
        exclusively to detect UPI transaction alerts 
        sent by Indian banks (HDFC, SBI, ICICI, Axis, 
        Kotak, and others).
      </p>
      <div class="highlight-box">
        <p>
          SMS messages are processed entirely on your 
          device. Raw SMS content is never transmitted 
          to our servers, stored in any external 
          database, or shared with any third party. 
          Only the extracted transaction data (amount, 
          merchant name, date) is saved to your 
          private account.
        </p>
      </div>
      <p>
        We do not read personal messages, OTPs, 
        promotional messages, or any non-financial SMS.
      </p>
    </div>

    <div class="section">
      <h2>3. Google Sign-In</h2>
      <p>
        Orbit uses Google Sign-In for account creation 
        and login. We request only the minimum required 
        permissions:
      </p>
      <ul>
        <li>Your name</li>
        <li>Your email address</li>
        <li>Your profile picture</li>
      </ul>
      <div class="highlight-box">
        <p>
          We do not request access to your Gmail inbox, 
          Gmail messages, or any Google account data 
          beyond your basic profile information. Orbit 
          does not read, access, store, or process your 
          emails in any way.
        </p>
      </div>
    </div>

    <div class="section">
      <h2>4. Notifications</h2>
      <p>
        Orbit requests notification permission to 
        send you:
      </p>
      <ul>
        <li>EMI due date reminders (2 days before 
          your EMI is due)</li>
        <li>Recurring charge reminders (2 days before 
          a detected recurring charge)</li>
      </ul>
      <p>
        We do not send promotional notifications, 
        advertising notifications, or any notification 
        unrelated to your own financial data. You can 
        disable notifications at any time from your 
        device settings.
      </p>
    </div>

    <div class="section">
      <h2>5. How We Use Your Data</h2>
      <ul>
        <li>To display your transaction history and 
          spending analytics</li>
        <li>To categorise transactions automatically</li>
        <li>To detect recurring charges and EMI 
          patterns from your transactions</li>
        <li>To send EMI and recurring charge 
          reminders</li>
        <li>To calculate your daily average spend, 
          weekly spend, and monthly totals</li>
        <li>To personalise the app experience with 
          your name and preferences</li>
      </ul>
      <div class="highlight-box">
        <p>
          We do not use your data for advertising. 
          We do not sell your data to any third party. 
          We do not share your data with any third 
          party for any purpose other than operating 
          the app.
        </p>
      </div>
    </div>

    <div class="section">
      <h2>6. Data Storage</h2>
      <p>
        Your financial data is stored securely in our 
        database with encryption in transit and at 
        rest. We use industry-standard security 
        practices to protect your data.
      </p>
      <p>
        We retain your data for as long as your account 
        is active. When you delete your account, all 
        your data is permanently deleted from our 
        systems within 30 days.
      </p>
    </div>

    <div class="section">
      <h2>7. Third-Party Services</h2>
      <p>
        Orbit uses the following third-party services 
        to operate:
      </p>
      <ul>
        <li>
          <strong style="color:#ffffff">
            Google Sign-In
          </strong> — for account authentication. 
          Google's Privacy Policy applies to data 
          processed through their service.
        </li>
        <li>
          <strong style="color:#ffffff">
            Supabase
          </strong> — for secure data storage. 
          Supabase's Privacy Policy applies.
        </li>
        <li>
          <strong style="color:#ffffff">
            Firebase Cloud Messaging
          </strong> — for delivering push notifications 
          to your device.
        </li>
      </ul>
      <p>
        We do not use advertising SDKs or analytics 
        platforms that share your data with 
        third parties.
      </p>
    </div>

    <div class="section">
      <h2>8. Data Safety</h2>
      <ul>
        <li>All data is encrypted in transit 
          using HTTPS</li>
        <li>All data is encrypted at rest</li>
        <li>We follow Google Play's data safety 
          requirements</li>
        <li>We never sell user data</li>
        <li>We never share user data for 
          advertising purposes</li>
        <li>Raw SMS content never leaves 
          your device</li>
      </ul>
    </div>

    <div class="section">
      <h2>9. Your Rights</h2>
      <ul>
        <li>
          <strong style="color:#ffffff">
            Access:
          </strong>
          View all your data inside the app
        </li>
        <li>
          <strong style="color:#ffffff">
            Correction:
          </strong>
          Edit your profile at any time
        </li>
        <li>
          <strong style="color:#ffffff">
            Deletion:
          </strong>
          Delete your account and all data from 
          Profile → Settings → Delete Account
        </li>
        <li>
          <strong style="color:#ffffff">
            Revoke permissions:
          </strong>
          Remove SMS or notification access from 
          Android Settings → Apps → Orbit → 
          Permissions at any time
        </li>
      </ul>
    </div>

    <div class="section">
      <h2>10. Children's Privacy</h2>
      <p>
        Orbit is intended for users 18 years and older. 
        We do not knowingly collect data from anyone 
        under 18. If we become aware that a child under 
        18 has provided us with personal information, 
        we will delete it immediately.
      </p>
    </div>

    <div class="section">
      <h2>11. Guest Mode</h2>
      <p>
        Orbit offers a guest mode that allows you to 
        use the app without creating an account. In 
        guest mode, all your data is stored locally 
        on your device only and is never transmitted 
        to our servers.
      </p>
    </div>

    <div class="section">
      <h2>12. Changes to This Policy</h2>
      <p>
        We may update this policy from time to time. 
        The "Last updated" date at the top will reflect 
        any changes. We will notify you of significant 
        changes via a notification in the app. 
        Continued use of the app after changes means 
        you accept the updated policy.
      </p>
    </div>

    <div class="section">
      <h2>13. Contact Us</h2>
      <p>
        For privacy questions, data deletion requests, 
        or any concerns:
      </p>
      <ul>
        <li>
          Email:
          <a href="mailto:privacy@orbitapp.in">
            privacy@orbitapp.in
          </a>
        </li>
        <li>App: Orbit — UPI Money Tracker</li>
      </ul>
      <p>
        We will respond to all privacy requests 
        within 7 business days.
      </p>
    </div>

    <div class="footer">
      <span>© 2026 Orbit · Made in India 🇮🇳</span>
      <span>
        <a href="mailto:privacy@orbitapp.in">
          privacy@orbitapp.in
        </a>
      </span>
    </div>

  </div>
</body>
</html>
