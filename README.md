**Installation & Setup:**
-------------------------------
[OhMyZ.sh](https://ohmyz.sh/#install)

[Amphetamine](https://apps.apple.com/us/app/amphetamine/id937984704?mt=12)

[Amphetamine Enhancer](https://github.com/x74353/Amphetamine-Enhancer)

[Toothpicks](https://apps.apple.com/us/app/toothpicks/id998361254?mt=12)

[PopClip Extensions](https://pilotmoon.com/popclip/extensions/)

[Homebrew](https://brew.sh/)
- [Brewfile](MacOS-Setup\Brewfile)

Alfred Workflows:
---------------------------
- Alred Preferences File.zip, redeploy according to the file path.
- Need more Workflows? Seek them here: [Packal - Alfred](https://www.packal.org/)

Chrome Extensions:
--------------------------------
[TamperMonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) - Make sure to install ChatGPT UserScript (my repo)
[Check My Links](https://chrome.google.com/webstore/detail/check-my-links/ojkcdipcgfaekbeaelaapakgnjflfglf)
[Dropmark](https://chrome.google.com/webstore/detail/add-to-dropmark/foiapgoppijipmmgkaibacckkhbngfhp/related)
[Google Dictionary](https://chrome.google.com/webstore/detail/google-dictionary-by-goog/mgijmajocgfcbeboacabfgobmjgjcoja/related)
[JSONView](https://chrome.google.com/webstore/detail/jsonvue/chklaanhfefbnpoihckbnefhakgolnmc/related)
[LinkClump](https://chrome.google.com/webstore/detail/linkclump/lfpjkncokllnfokkgpkobnkbkmelfefj/related)
[OctoLinker](https://chrome.google.com/webstore/detail/octolinker/jlmafbaeoofdegohdhinkhilhclaklkp/related)
[Octotree](https://chrome.google.com/webstore/detail/octotree-github-code-tree/bkhaagjahfmjljalopjnoealnfndnagc)
[Postman Interceptor](https://chrome.google.com/webstore/detail/postman-interceptor/aicmkgpgakddgnaphhhpliifpcfhicfo/related)
[uBlock Origin](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm/related)
[tlda](https://chrome.google.com/webstore/detail/tlda/ogefhmcfhgggggefddkaemfifdcljbml/related)
[Stylish](https://chrome.google.com/webstore/detail/stylish-custom-themes-for/fjnbnpbmkenffdnngjfgmeleoegfcffe/related)
[Vue.js devtools](https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd/related)
[YouTube Playback Speed Control](https://chrome.google.com/webstore/detail/youtube-playback-speed-co/hdannnflhlmdablckfkjpleikpphncik)
[YouTube - SponsorBlock](https://chrome.google.com/webstore/detail/sponsorblock-for-youtube/mnjggcdmjocbbbhaepdhchncahnbgone)

Script:
----------
```
# run at chrome://extensions
output = []
document.querySelectorAll(".extension-details").forEach(el => {
    var title = el.querySelector(".extension-title").textContent.trim()
    var id = el.querySelector(".extension-id").textContent.trim()
    var link = `https://chrome.google.com/webstore/detail/${id}`
    output.push(`* [${title}](${link})`)
})
copy(output.join("\n"))
```


Setup [BrewUp](https://github.com/fire1ce/BrewUp)