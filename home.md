---
layout: home
permalink: /home/
---

<script>
  if (!sessionStorage.getItem("accessGranted")) {
    window.location.href = "/";
  }

  function logout() {
    sessionStorage.removeItem("accessGranted");
    window.location.href = "/";
  }
</script>

<button onclick="logout()" style="margin-bottom:20px;">
  Logout
</button>
