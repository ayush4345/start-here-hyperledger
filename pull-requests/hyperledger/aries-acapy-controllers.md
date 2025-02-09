---
layout: default
title: aries-acapy-controllers
parent: Hyperledger
grand_parent: Pull Requests
has_children: false
permalink: /pull-requests/hyperledger/aries-acapy-controllers
---

# aries-acapy-controllers <span class="fs-3 right-align">[GitHub](https://github.com/hyperledger/aries-acapy-controllers){: .btn .mr-4 }</span>


<div>
    <table>
        <tr>
            <td>
                PR <a href="https://github.com/hyperledger/aries-acapy-controllers/pull/84" class=".btn">#84</a>
            </td>
            <td>
                <b>
                    Bump jszip from 3.7.1 to 3.10.1 in /AliceFaberAcmeDemo/controllers/alice-controller
                </b>
            </td>
        </tr>
        <tr>
            <td>
                <span class="chip">dependencies</span><span class="chip">javascript</span>
            </td>
            <td>
                Bumps [jszip](https://github.com/Stuk/jszip) from 3.7.1 to 3.10.1.
<details>
<summary>Changelog</summary>
<p><em>Sourced from <a href="https://github.com/Stuk/jszip/blob/main/CHANGES.md">jszip's changelog</a>.</em></p>
<blockquote>
<h3>v3.10.1 2022-08-02</h3>
<ul>
<li>Add sponsorship files.
<ul>
<li>If you appreciate the time spent maintaining JSZip then I would really appreciate <a href="https://github.com/sponsors/Stuk">your sponsorship</a>.</li>
</ul>
</li>
<li>Consolidate metadata types and expose OnUpdateCallback <a href="https://github-redirect.dependabot.com/Stuk/jszip/pull/851">#851</a> and <a href="https://github-redirect.dependabot.com/Stuk/jszip/pull/852">#852</a></li>
<li>use <code>const</code> instead <code>var</code> in example from README.markdown <a href="https://github-redirect.dependabot.com/Stuk/jszip/pull/828">#828</a></li>
<li>Switch manual download link to HTTPS <a href="https://github-redirect.dependabot.com/Stuk/jszip/pull/839">#839</a></li>
</ul>
<p>Internals:</p>
<ul>
<li>Replace jshint with eslint <a href="https://github-redirect.dependabot.com/Stuk/jszip/pull/842">#842</a></li>
<li>Add performance tests <a href="https://github-redirect.dependabot.com/Stuk/jszip/pull/834">#834</a></li>
</ul>
<h3>v3.10.0 2022-05-20</h3>
<ul>
<li>Change setimmediate dependency to more efficient one. Fixes <a href="https://github-redirect.dependabot.com/Stuk/jszip/issues/617">Stuk/jszip#617</a> (see <a href="https://github-redirect.dependabot.com/Stuk/jszip/pull/829">#829</a>)</li>
<li>Update types of <code>currentFile</code> metadata to include <code>null</code> (see <a href="https://github-redirect.dependabot.com/Stuk/jszip/pull/826">#826</a>)</li>
</ul>
<h3>v3.9.1 2022-04-06</h3>
<ul>
<li>Fix recursive definition of <code>InputFileFormat</code> introduced in 3.9.0.</li>
</ul>
<h3>v3.9.0 2022-04-04</h3>
<ul>
<li>Update types JSZip#loadAsync to accept a promise for data, and remove arguments from <code>new JSZip()</code> (see <a href="https://github-redirect.dependabot.com/Stuk/jszip/pull/752">#752</a>)</li>
<li>Update types for <code>compressionOptions</code> to JSZipFileOptions and JSZipGeneratorOptions (see <a href="https://github-redirect.dependabot.com/Stuk/jszip/pull/722">#722</a>)</li>
<li>Add types for <code>generateInternalStream</code> (see <a href="https://github-redirect.dependabot.com/Stuk/jszip/pull/774">#774</a>)</li>
</ul>
<h3>v3.8.0 2022-03-30</h3>
<ul>
<li>Santize filenames when files are loaded with <code>loadAsync</code>, to avoid <a href="https://snyk.io/research/zip-slip-vulnerability">&quot;zip slip&quot; attacks</a>. The original filename is available on each zip entry as <code>unsafeOriginalName</code>. See the <a href="https://stuk.github.io/jszip/documentation/api_jszip/load_async.html">documentation</a>. Many thanks to McCaulay Hudson for reporting.</li>
</ul>
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a href="https://github.com/Stuk/jszip/commit/0f2f1e4d0509514417db83fe5b86bde90e0ffe8d"><code>0f2f1e4</code></a> 3.10.1</li>
<li><a href="https://github.com/Stuk/jszip/commit/cae55105f5e8bd37c270cdb76eab2cf40388dfd9"><code>cae5510</code></a> Updates for v3.10.1</li>
<li><a href="https://github.com/Stuk/jszip/commit/179c9a0340477985b82734f1b09560411adb5b94"><code>179c9a0</code></a> Update changelog for 3.10.1</li>
<li><a href="https://github.com/Stuk/jszip/commit/61e1df58dac54eec1e9733649638518b79896731"><code>61e1df5</code></a> Add Jekyll files to gitignore</li>
<li><a href="https://github.com/Stuk/jszip/commit/f299cce9b8d9e2be11db997919cf1777167902b7"><code>f299cce</code></a> Merge pull request <a href="https://github-redirect.dependabot.com/Stuk/jszip/issues/852">#852</a> from Stuk/metadata-ts</li>
<li><a href="https://github.com/Stuk/jszip/commit/852887aa9483c552cd88e4eb8c298a475c0f9269"><code>852887a</code></a> Consolidate metadata types and expose OnUpdateCallback</li>
<li><a href="https://github.com/Stuk/jszip/commit/5be00dfd0cc86c948420901e911e2b0fb286f19a"><code>5be00df</code></a> Add sponsorship files</li>
<li><a href="https://github.com/Stuk/jszip/commit/dabe86445ce60705936ad15830c817ccb182e649"><code>dabe864</code></a> Update package-lock for benchmark</li>
<li><a href="https://github.com/Stuk/jszip/commit/cc554dae51d306fe0f188891f33e16cb6d81372d"><code>cc554da</code></a> Merge pull request <a href="https://github-redirect.dependabot.com/Stuk/jszip/issues/841">#841</a> from stevennyman/patch-2</li>
<li><a href="https://github.com/Stuk/jszip/commit/caefbc082d4bed536207fe473819fc91041d4f65"><code>caefbc0</code></a> Merge pull request <a href="https://github-redirect.dependabot.com/Stuk/jszip/issues/834">#834</a> from Stuk/benchmark</li>
<li>Additional commits viewable in <a href="https://github.com/Stuk/jszip/compare/v3.7.1...v3.10.1">compare view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=jszip&package-manager=npm_and_yarn&previous-version=3.7.1&new-version=3.10.1)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

Dependabot will resolve any conflicts with this PR as long as you don't alter it yourself. You can also trigger a rebase manually by commenting `@dependabot rebase`.

[//]: # (dependabot-automerge-start)
[//]: # (dependabot-automerge-end)

---

<details>
<summary>Dependabot commands and options</summary>
<br />

You can trigger Dependabot actions by commenting on this PR:
- `@dependabot rebase` will rebase this PR
- `@dependabot recreate` will recreate this PR, overwriting any edits that have been made to it
- `@dependabot merge` will merge this PR after your CI passes on it
- `@dependabot squash and merge` will squash and merge this PR after your CI passes on it
- `@dependabot cancel merge` will cancel a previously requested merge and block automerging
- `@dependabot reopen` will reopen this PR if it is closed
- `@dependabot close` will close this PR and stop Dependabot recreating it. You can achieve the same result by closing it manually
- `@dependabot ignore this major version` will close this PR and stop Dependabot creating any more for this major version (unless you reopen the PR or upgrade to it yourself)
- `@dependabot ignore this minor version` will close this PR and stop Dependabot creating any more for this minor version (unless you reopen the PR or upgrade to it yourself)
- `@dependabot ignore this dependency` will close this PR and stop Dependabot creating any more for this dependency (unless you reopen the PR or upgrade to it yourself)
- `@dependabot use these labels` will set the current labels as the default for future PRs for this repo and language
- `@dependabot use these reviewers` will set the current reviewers as the default for future PRs for this repo and language
- `@dependabot use these assignees` will set the current assignees as the default for future PRs for this repo and language
- `@dependabot use this milestone` will set the current milestone as the default for future PRs for this repo and language

You can disable automated security fix PRs for this repo from the [Security Alerts page](https://github.com/hyperledger/aries-acapy-controllers/network/alerts).

</details>
            </td>
        </tr>
    </table>
    <div class="right-align">
        Created At 2023-02-02 18:45:11 +0000 UTC
    </div>
</div>

<div>
    <table>
        <tr>
            <td>
                PR <a href="https://github.com/hyperledger/aries-acapy-controllers/pull/83" class=".btn">#83</a>
            </td>
            <td>
                <b>
                    Bump ua-parser-js from 0.7.31 to 0.7.33 in /AliceFaberAcmeDemo/controllers/alice-controller
                </b>
            </td>
        </tr>
        <tr>
            <td>
                <span class="chip">dependencies</span><span class="chip">javascript</span>
            </td>
            <td>
                Bumps [ua-parser-js](https://github.com/faisalman/ua-parser-js) from 0.7.31 to 0.7.33.
<details>
<summary>Changelog</summary>
<p><em>Sourced from <a href="https://github.com/faisalman/ua-parser-js/blob/master/changelog.md">ua-parser-js's changelog</a>.</em></p>
<blockquote>
<h2>Version 0.7.31 / 1.0.2</h2>
<ul>
<li>Fix OPPO Reno A5 incorrect detection</li>
<li>Fix TypeError Bug</li>
<li>Use AST to extract regexes and verify them with safe-regex</li>
</ul>
<h2>Version 0.7.32 / 1.0.32</h2>
<ul>
<li>Add new browser : DuckDuckGo, Huawei Browser, LinkedIn</li>
<li>Add new OS : HarmonyOS</li>
<li>Add some Huawei models</li>
<li>Add Sharp Aquos TV</li>
<li>Improve detection Xiaomi Mi CC9</li>
<li>Fix Sony Xperia 1 III misidentified as Acer tablet</li>
<li>Fix Detect Sony BRAVIA as SmartTV</li>
<li>Fix Detect Xiaomi Mi TV as SmartTV</li>
<li>Fix Detect Galaxy Tab S8 as tablet</li>
<li>Fix WeGame mistakenly identified as WeChat</li>
<li>Fix included commas in Safari / Mobile Safari version</li>
<li>Increase UA_MAX_LENGTH to 350</li>
</ul>
<h2>Version 0.7.33 / 1.0.33</h2>
<ul>
<li>Add new browser : Cobalt</li>
<li>Identify Macintosh as an Apple device</li>
<li>Fix ReDoS vulnerability</li>
</ul>
<h1>Version 0.8</h1>
<p>Version 0.8 was created by accident. This version is now deprecated and no longer maintained, please update to version 0.7 / 1.0.</p>
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a href="https://github.com/faisalman/ua-parser-js/commit/f2d0db001d87da15de7b9b1df7be9f2eacefd8c5"><code>f2d0db0</code></a> Bump version 0.7.33</li>
<li><a href="https://github.com/faisalman/ua-parser-js/commit/a6140a17dd0300a35cfc9cff999545f267889411"><code>a6140a1</code></a> Remove unsafe regex in trim() function</li>
<li><a href="https://github.com/faisalman/ua-parser-js/commit/a88660493568d6144a551424a8139d6c876635f6"><code>a886604</code></a> Fix <a href="https://github-redirect.dependabot.com/faisalman/ua-parser-js/issues/605">#605</a> - Identify Macintosh as Apple device</li>
<li><a href="https://github.com/faisalman/ua-parser-js/commit/b814bcd79198e730936c82462e2d729eb5423e3c"><code>b814bcd</code></a> Merge pull request <a href="https://github-redirect.dependabot.com/faisalman/ua-parser-js/issues/606">#606</a> from rileyjshaw/patch-1</li>
<li><a href="https://github.com/faisalman/ua-parser-js/commit/7f71024161399b7aa5d5cd10dba9e059f0218262"><code>7f71024</code></a> Fix documentation</li>
<li><a href="https://github.com/faisalman/ua-parser-js/commit/c239ac5167abd574a635cb809a2b4fa35810d23b"><code>c239ac5</code></a> Merge pull request <a href="https://github-redirect.dependabot.com/faisalman/ua-parser-js/issues/604">#604</a> from obecerra3/master</li>
<li><a href="https://github.com/faisalman/ua-parser-js/commit/8d3c2d327cf540ff2c050f1cc67bca8c6f8e4458"><code>8d3c2d3</code></a> Add new browser: Cobalt</li>
<li><a href="https://github.com/faisalman/ua-parser-js/commit/d11fc47dc9b6acc0f89fc10c120cea08e10cd31a"><code>d11fc47</code></a> Bump version 0.7.32</li>
<li><a href="https://github.com/faisalman/ua-parser-js/commit/b490110109de586deab96c775c9ef0dfc9c919c4"><code>b490110</code></a> Merge branch 'develop' of github.com:faisalman/ua-parser-js</li>
<li><a href="https://github.com/faisalman/ua-parser-js/commit/cb5da5ea4b220d5b60fe209e123b7f911d8e0d4a"><code>cb5da5e</code></a> Merge pull request <a href="https://github-redirect.dependabot.com/faisalman/ua-parser-js/issues/600">#600</a> from moekm/develop</li>
<li>Additional commits viewable in <a href="https://github.com/faisalman/ua-parser-js/compare/0.7.31...0.7.33">compare view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=ua-parser-js&package-manager=npm_and_yarn&previous-version=0.7.31&new-version=0.7.33)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

Dependabot will resolve any conflicts with this PR as long as you don't alter it yourself. You can also trigger a rebase manually by commenting `@dependabot rebase`.

[//]: # (dependabot-automerge-start)
[//]: # (dependabot-automerge-end)

---

<details>
<summary>Dependabot commands and options</summary>
<br />

You can trigger Dependabot actions by commenting on this PR:
- `@dependabot rebase` will rebase this PR
- `@dependabot recreate` will recreate this PR, overwriting any edits that have been made to it
- `@dependabot merge` will merge this PR after your CI passes on it
- `@dependabot squash and merge` will squash and merge this PR after your CI passes on it
- `@dependabot cancel merge` will cancel a previously requested merge and block automerging
- `@dependabot reopen` will reopen this PR if it is closed
- `@dependabot close` will close this PR and stop Dependabot recreating it. You can achieve the same result by closing it manually
- `@dependabot ignore this major version` will close this PR and stop Dependabot creating any more for this major version (unless you reopen the PR or upgrade to it yourself)
- `@dependabot ignore this minor version` will close this PR and stop Dependabot creating any more for this minor version (unless you reopen the PR or upgrade to it yourself)
- `@dependabot ignore this dependency` will close this PR and stop Dependabot creating any more for this dependency (unless you reopen the PR or upgrade to it yourself)
- `@dependabot use these labels` will set the current labels as the default for future PRs for this repo and language
- `@dependabot use these reviewers` will set the current reviewers as the default for future PRs for this repo and language
- `@dependabot use these assignees` will set the current assignees as the default for future PRs for this repo and language
- `@dependabot use this milestone` will set the current milestone as the default for future PRs for this repo and language

You can disable automated security fix PRs for this repo from the [Security Alerts page](https://github.com/hyperledger/aries-acapy-controllers/network/alerts).

</details>
            </td>
        </tr>
    </table>
    <div class="right-align">
        Created At 2023-01-27 10:29:42 +0000 UTC
    </div>
</div>

