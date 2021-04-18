[![Build](https://travis-ci.org/gorhill/uBlock.svg?branch=master)](https://travis-ci.org/gorhill/uBlock)
[![Crowdin](https://d322cqt584bo4o.cloudfront.net/ublock/localized.svg)](https://crowdin.com/project/ublock)
[![License](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://github.com/gorhill/uBlock/blob/master/LICENSE.txt)

*** 

<h1 align="center">
<sub>
<img  src="https://raw.githubusercontent.com/gorhill/uBlock/master/doc/img/icon38@2x.png" height="38" width="38">
</sub>
uBlock Origin
</h1>
<p align="center">
<sup> <!-- Pronounciation -->
      <i>유-블록 오리진</i>  이라고 부릅니다(<code>/ˈjuːˌblɒk/</code>) — <i>당신</i>이 원하는대로 브라우저를 만들어 보세요.
</sup>
<br>
<sup> <!-- Languages -->
      <img src="https://raw.githubusercontent.com/gorhill/uBlock/master/doc/img/languageicon-36.png" width="18" height="18">
      <sup>
            Korean (한국어),
                        <a href="https://github.com/gorhill/uBlock/blob/master/README.md">English</a>,
            <a href="https://github.com/fang5566/uBlock/blob/master/README.md#ublock-origin">Chinese (中文)</a>,
            <a href="https://github.com/ialexsilva/uBlock/blob/master/README.md#ublock-origin">Português (Brasil)</a>
      </sup>
</sup>
<br>
<sub><a href="https://github.com/gorhill/uBlock/wiki/uBlock-Origin-is-completely-unrelated-to-the-web-site-ublock.org"><b>주의하세요!</b> uBlock Origin은 <code>ublock.org</code>와 전혀 상관 없습니다</a>.</sub>
</p>

***

<p align="center">
<a href="https://addons.mozilla.org/addon/ublock-origin/"><img src="https://user-images.githubusercontent.com/585534/107280546-7b9b2a00-6a26-11eb-8f9f-f95932f4bfec.png" alt="Get uBlock Origin for Firefox"></a> 
<a href="https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm"><img src="https://user-images.githubusercontent.com/585534/107280622-91a8ea80-6a26-11eb-8d07-77c548b28665.png" alt="Get uBlock Origin for Chromium"></a>
<a href="https://microsoftedge.microsoft.com/addons/detail/odfafepnkmbhccpbejgmiehpchacaeak"><img src="https://user-images.githubusercontent.com/585534/107280673-a5ece780-6a26-11eb-9cc7-9fa9f9f81180.png" alt="Get uBlock Origin for Microsoft Edge"></a>
<a href="https://addons.opera.com/extensions/details/ublock/"><img src="https://user-images.githubusercontent.com/585534/107280692-ac7b5f00-6a26-11eb-85c7-088926504452.png" alt="Get uBlock Origin for Opera"></a>
      <br><sub><a href="https://twitter.com/gorhill/status/1033706103782170625">다른 광고 차단 프로그램들과 <b>절대로</b> 같이 사용하지 마세요</a>.</sub>
      <br><sub><a href="#installation">아래</a>에 더 많은 설치 방법들이 있습니다.</sub>
</p>

***

**다양한 브라우저를 위한 빠르고, 강력하고, 효율적인 차단 프로그램**

uBlock Origin은 단순한 광고 차단 기능만 하는 프로그램이 **아닌**, [범용적인 차단 프로그램 입니다](https://github.com/gorhill/uBlock/wiki/Blocking-mode). uBlock Origin은 [_EasyList_](https://easylist.github.io/#easylist), [_EasyPrivacy_](https://easylist.github.io/#easyprivacy), [_Peter Lowe’s ad/tracking/malware servers_](https://pgl.yoyo.org/adservers/policy.php), [_Online Malicious URL Blocklist_](https://gitlab.com/curben/urlhaus-filter#urlhaus-malicious-url-blocklist), 그리고 uBlock Origin의 [자체적 필터들](https://github.com/uBlockOrigin/uAssets/tree/master/filters)과 함께 설치되어 광고, 추적 프로그램, 악성 사이트들을 차단합니다.

***

* [설명서](#설명서)
* [일반 정보](#우리의-철학)
* [설치방법](#설치-방법)
  * [Chromium](#chromium)
  * [Firefox](#firefox--firefox-for-android)
  * [Microsoft Edge](#microsoft-edge)
  - [Safari (macOS)](#safari-macos)
* [릴리즈 내역](#릴리즈-내역)
* [개인정보 보호 방침](https://github.com/gorhill/uBlock/wiki/Privacy-policy)
* [위키](https://github.com/gorhill/uBlock/wiki)

## 설명서

 기본 모드 | 고급 사용자 모드
:----------:|:------------------:
[팝업 유저 인터페이스](https://github.com/gorhill/uBlock/wiki/Quick-guide:-popup-user-interface) | [클릭 한번으로 사이트별 차단 설정](https://github.com/gorhill/uBlock/wiki/Dynamic-filtering:-quick-guide) 
<a href="https://github.com/gorhill/uBlock/wiki/Quick-guide:-popup-user-interface"><img src="https://user-images.githubusercontent.com/585534/84045360-b10ee580-a976-11ea-9e91-29c2107b47c2.png" /></a><br><sup>.<br>.</sup> | <a href="https://github.com/gorhill/uBlock/wiki/Dynamic-filtering:-quick-guide"><img src="https://user-images.githubusercontent.com/585534/84045366-b1a77c00-a976-11ea-9121-e8c8f35c66c8.png" /></a><br><sup>원하는 대로 설정 할 수 있습니다<br>사진: 모든 웹사이트에서 외부 스크립트와 외부 프레임을 차단함 </sup>

[uBlock Origin 위키](https://github.com/gorhill/uBlock/wiki)를 방문해 더 많은 내용을 살펴보세요.

질문이나 도움이 필요하다면 서브레딧 [/r/uBlockOrigin](https://www.reddit.com/r/uBlockOrigin/)을 사용해 보세요.

## 우리의 철학

uBlock Origin (또는 uBlock₀) 단순한 *광고 차단 프로그램* 이 아닌, 여러가지 상황에서 쓸 수 있는 범용 차단 프로그램 입니다. uBlock Origin은 [Adblock Plus 필터 구문](https://adblockplus.org/en/filters)을 이용해 광고를 차단합니다. uBlock Origin 은 확장된 [문법들](https://github.com/gorhill/uBlock/wiki/Filter-syntax-extensions) 을 통하여 사용자가 만든 규칙들과 필터를 사용할수 있도록 만들어 졌습니다. Furthermore, advanced mode allows uBlock Origin to work in [default-deny mode](https://github.com/gorhill/uBlock/wiki/Dynamic-filtering:-default-deny), which mode will cause [all 3rd-party network requests](https://requestpolicycontinued.github.io/#what-are-cross-site-requests) to be blocked by default, unless allowed by the user.

기억해두세요, 이 차단 프로그램을 사용하는것은, *절대로* [도둑질을 하는것](https://twitter.com/LeaVerou/status/518154828166725632)이  아닙니다. Don't fall for this creepy idea. The _ultimate_ logical consequence of `광고 차단 프로그램을 사용하는것 = 도둑질이다` is the criminalisation of the inalienable right to privacy.

Ads, "unintrusive" or not, are just the visible portions of privacy-invading apparatus entering your browser when you visit most sites nowadays. **uBlock Origin's main goal is to help users neutralize such privacy-invading apparatus** — in a way that welcomes those users who don't wish to use more technical, involved means (such as [uMatrix](https://github.com/gorhill/uMatrix)).

_EasyList_, _EasyPrivacy_, _Peter Lowe's_, _Online Malicious URL Blocklist_ 그리고 uBO의 자체 필터들과 함께 설치되고, 기본적으로 활성화 됩니다. Many more lists are readily available to block trackers, analytics, and more.Hosts 파일 또한 지원됩니다.

uBlock Origin을 설치한 후, 너무 필터가 너무 많은것들을 차단한다고 생각하시면, 여러분은 쉽게 기본 필터를 비활성화 할수 있습니다. Adblock Plus의 경우 _EasyList_ 만 기본적으로 활성화 되어 있습니다.

## 설치 방법

기회가 된다면 [프로그램이 필요하는 권한 목록](https://github.com/gorhill/uBlock/wiki/Permissions)을 읽어 보세요.

#### Chromium

최신 버전을 [수동](https://github.com/gorhill/uBlock/tree/master/dist#install)으로 설치하거나, [크롬 웹스토어](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm), 혹은 [오페라 애드온 웹사이트](https://addons.opera.com/extensions/details/ublock/)를 통해 설치할수 있습니다.

There is also a development version in the Chrome Web Store if you want to test uBlock Origin with the latest changes: see [_uBlock Origin dev build_](https://chrome.google.com/webstore/detail/ublock-origin-dev-build/cgbcahbpdhpcegmbfconppldiemgcoii).

uBlock Origin은 어떠한 크로미움 기반 브라우저에도 적용될수 있도록 설계되었습니다.

#### Firefox / Firefox for android

[Firefox 애드온 웹사이트](https://addons.mozilla.org/addon/ublock-origin/)

uBlock Origin의 테스트 버전을 사용해보고 싶으시다면, [Install / Firefox webext / For beta version](https://github.com/gorhill/uBlock/blob/master/dist/README.md#for-beta-version)를 확인해 주세요.

uBlock Origin은 [SeaMonkey](http://www.seamonkey-project.org/), [Pale Moon](https://www.palemoon.org/) 그리고 Firefox 기반 브라우저들과 호환됩니다. 설치를 위해서는 [Install / Firefox legacy](https://github.com/gorhill/uBlock/blob/master/dist/README.md#firefox-legacy)를 확인해 주세요.

[데비안 패키지 매니저](https://packages.debian.org/stable/source/ublock-origin)를 통해서도 uBlock Origin을 설치 할수 있습니다:

- Firefox 56 이하: `apt-get install xul-ext-ublock-origin`
- Firefox 55 이상: `apt-get install webext-ublock-origin`

There is no guarantee the package will be available on your specific platform -- in which case, you will have to install from [Firefox Add-ons web site](https://addons.mozilla.org/addon/ublock-origin/).

#### Microsoft Edge

제작자: [Nik Rolls](https://github.com/nikrolls/uBlock-Edge)

크로미움 기반 Edge: [Edge 에드온 웹사이트](https://microsoftedge.microsoft.com/addons/detail/odfafepnkmbhccpbejgmiehpchacaeak).

#### Safari (macOS)

개발자: [@el1t](https://github.com/el1t)

테스트 버전을 설치 해볼수 있습니다. <https://github.com/el1t/uBlock-Safari#ublock-originfor-safari>

주의하세요! Safari 13 이상에서는 uBlock Origin과 같은 프로그램들이 작동하지 않습니다 <https://github.com/el1t/uBlock-Safari/issues/158>를 확인해 보세요.

현재 Safari는 포크 메인테이터에 의해서 관리중입니다, uBlock Origin은 코드 베이스에 대한 권한이 없습니다.

#### 브라우저 공통

uBlock Origin의 효율을 극대화 하기 위해, 다른 차단 프로그램들(Adblock Plus, AdBlock)과 같이 사용하지 마세요. uBlock Origin은 유명한 다른 차단 프로그램들보다 [더 높거나 같은](#blocking) 성능을 갖고 있습니다. 다른 차단 프로그램과 함께 사용하면 uBlock Origin의 개인정보 보호기능, 차단 회피 방해 기능들이 작동하는것을 방해 할수도 있습니다.

#### 그룹 배포

아래 내용은 그룹 관리자가 그룹에 uBlock Origin을 설치하는 방법에 대해 소개합니다.

- [uBlock Origin 배포하기](https://github.com/gorhill/uBlock/wiki/Deploying-uBlock-Origin)
    - Firefox: [CCK2와 그룹 정책으로 Firefox 설치하기](http://decentsecurity.com/ublock-for-firefox-deployment/) (외부링크)
    - Google Chrome: [Google Chrome 광고차단 기능 추가하기](https://decentsecurity.com/ublock-for-google-chrome-deployment/) (외부링크)

## 릴리즈 내역

[릴리즈 페이지](https://github.com/gorhill/uBlock/releases) 에서 릴리즈 내역과 릴리즈에 대한 하이라이트 부분을 볼 수 있습니다.

## 정보

[uBlock Origin의 원칙](MANIFESTO.md)

무료이며, 오픈소스이며, 사용자의, 사용자에 의한, 사용자를 위한 프로그램입니다. 어떠한 기부도 바라지 않습니다.

이 프로그램에 포함되어 있는 필터가 없다면, 이 프로그램은 쓸모가 없어집니다. 그러니 어떤것이라도 기여하고 싶은 마음이 든신다면, 무료로 쓸 수 있게 만들어진 필터에 기여해 주세요.

여러분들은 uBlock Origin의 번역을 [Crowdin](https://crowdin.net/project/ublock)에서 도와 주실수 있습니다.

## 라이센스

[GPLv3](https://github.com/gorhill/uBlock/blob/master/LICENSE.txt).

## 번역 문의

Issuse 탭을 이용해 주세요.
