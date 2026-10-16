# Script check

If a holder's raw HTML runs on Pages, the line below says RAN.

<p id="probe">did not run</p>
<script>document.getElementById('probe').textContent = 'SCRIPT RAN';</script>

<style>#probe { color: rgb(255, 0, 0); }</style>
