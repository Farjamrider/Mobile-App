# Mobile-App
U.S.A
<!-- OneSignal SDK -->
<script src="https://cdn.onesignal.com/sdks/OneSignalSDK.js" async=""></script>

<script>
  window.OneSignal = window.OneSignal || [];
  OneSignal.push(function() {
    OneSignal.init({
      appId: "YOUR_APP_ID",  // اینجا باید App ID که از OneSignal گرفتید وارد کنید.
      safari_web_id: "YOUR_SAFARI_WEB_ID",  // اگر از Safari استفاده می‌کنید، این هم ضروریه.
      notifyButton: {
        enable: true,  // دکمه نوتیفیکیشن رو فعال می‌کنه
      }
    });
  });
</script>
