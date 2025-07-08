<!---
ICON=fa-solid fa-server
ROUTE=connect
SHORT=Connect
TITLE=Connect to Tuyosu
NAVBAR=true
FOOTER=false
BEHINDLOGIN=false
-->
### 1. The devserver method

1. Create a osu! shortcut
2. Right-Click it
3. Select propeties

Enter for target after the path for osu! ` -devserver tuyosu.de`

<input class="form-control" type="readonly" id="dev" value=" -devserver tuyosu.de"></input>

<a class="btn btn-info" onclick="copydev()">Copy devserver</a>

### 2. OLL Launcher

osu-server-list Launcher powered by <a href="https://osu-server-list.com/launcher">https://osu-server-list.com</a>

<a class="btn btn-info" target="_blank" href="https://osu-server-list.com/launcher">Download</a>

<script>
    function copydev() {
        var copyText = document.getElementById("dev");

        // Select the text field
        copyText.select();
        copyText.setSelectionRange(0, 99999); // For mobile devices

        // Copy the text inside the text field
        navigator.clipboard.writeText(copyText.value);

        // Alert the copied text
        alert("Copied the text: " + copyText.value);
    }
</script>
Do you still have issues? visit out <a href="https://discord.gg/sRBYT8xx2C">Discord</a>
