# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ko</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bko%5D%20low%20quality)


<!-- cache_translation_check_ko_e14a0181241f036d680a3cc9973aabc089321ba260f1ea8060b5beed4b631922 -->
```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>지갑 암호화 해제를 위해 입력된 비밀문구가 정확하지 않습니다. 비밀문구가 공백 문자 (0 바이트)를 포함하고 있습니다. 만약 비밀문구가 25.0 버전 이전의 비트코인 코어 소프트웨어에 의해 설정되었다면, 비밀문구를 첫 공백 문자 이전까지 입력해보세요. 이렇게 해서 성공적으로 입력되었다면, 차후 이런 문제가 발생하지 않도록 비밀문구를 새로이 설정해 주세요.</translation>
    
ERR
The translation incorrectly interprets "null character (ie - a zero byte)" as "공백 문자 (0 바이트)", which means "whitespace character (0 bytes)". In computing, a "null character" is "널 문자" in Korean, and it is not the same as a whitespace character. The rest of the translation is otherwise accurate, but this is a semantic error that could lead to misunderstanding.

Correct translation:
지갑 암호 해제를 위해 입력한 비밀번호가 올바르지 않습니다. 비밀번호에 널 문자(즉, 0 바이트)가 포함되어 있습니다. 만약 이 비밀번호가 25.0 이전 버전의 비트코인 코어 소프트웨어에서 설정된 것이라면, 첫 번째 널 문자까지만(첫 번째 널 문자를 포함하지 않고) 입력해 보세요. 이렇게 해서 성공했다면, 이러한 문제가 다시 발생하지 않도록 새 비밀번호를 설정해 주세요.
```

<!-- cache_translation_check_ko_e68de7a6f8664f6d4a4dd84edb0652c579f80457e823b08e0db3b58f815fefcd -->
```
        <source>About %1</source>
        <translation>%1 정보(A)</translation>
    
ERR
The translation "%1 정보(A)" is slightly problematic. In Korean UI terminology, "About" in "About %1" is typically translated as "%1 정보" without the "(A)" (which is often used as an English keyboard shortcut indicator; in Korean, shortcut keys are usually not indicated this way unless explicitly specified).

Correct translation:
%1 정보
```

<!-- cache_translation_check_ko_0708509c5abcebcdc6cdacd6ac569b52e7b5f1b2f235d137eae754712188dd90 -->
```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>지불 요청하기 (QR 코드와 bitcoin을 생성합니다: URIs)</translation>
    
ERR
The placement of 'bitcoin' and 'URIs' is incorrect, and the colon is misplaced. The translation should reflect that QR codes _and_ "bitcoin:" 형식의 URI를 생성함을 의미합니다. Additionally, the colon in "bitcoin:" is part of the URI scheme, not a list separator.

Correct translation:
지불 요청하기 (QR 코드와 bitcoin: URI를 생성합니다)
```

<!-- cache_translation_check_ko_1167509681d689c2d4764320291cbebc5e99d705f02d0758a4e3cb91b14e4aa5 -->
```
        <source>Ctrl+Q</source>
        <translation>Crtl + Q</translation>
    
ERR
There is a typo in the translation: "Crtl" should be "Ctrl" to match the standard keyboard shortcut notation.

Correct translation:
Ctrl+Q
```

<!-- cache_translation_check_ko_74578de58288b5dc630a6705ca05461eb57c711c2a16c7ec17a2e771308af691 -->
```
        <source>Load PSBT from clipboard…</source>
        <translation>PSBT 혹은 클립보드에서 불러오기</translation>
    
ERR
The translation changes the meaning. The English text says to load PSBT from the clipboard. The Korean translation says "PSBT or load from clipboard," which does not match the original. The word "혹은" means "or," which is incorrect here.

Correct translation:
클립보드에서 PSBT 불러오기…
```

<!-- cache_translation_check_ko_5fd26ed77f0a71bd6b5d66c7655e527dd9e03dea2fcf4cef40bad015f3075e6e -->
```
        <source>No wallets available</source>
        <translation>사용 가능한 블록이 없습니다.</translation>
    
ERR
The translation is erroneous. "사용 가능한 블록이 없습니다." means "No available blocks," which is incorrect. The English source says "No wallets available," referring to the lack of wallets, not blocks.

Correct translation:
사용 가능한 지갑이 없습니다.
```

<!-- cache_translation_check_ko_e219d8699d3c29f415479681efc99b55081f6cd5b2ec053a216edb324c48f6b7 -->
```
        <source>Copy label</source>
        <translation>복사  라벨</translation>
    
ERR
The translation uses incorrect word order and has an unnecessary double space. In Korean, the correct expression is "라벨 복사" or "라벨 복사하기".

Correct translation:
라벨 복사
```

<!-- cache_translation_check_ko_553628ad7aed874e5e6253d971ebfd31eab43c2b6cc3ce82f25f7faa5b449faa -->
```
        <source>Copy amount</source>
        <translation>복사  금액</translation>
    
ERR
There is an unnecessary space between "복사" and "금액", which creates a formatting issue. The correct translation should be:

Correct translation:
금액 복사
```

<!-- cache_translation_check_ko_e89229ba543ab8a194376c6aea48457c47ad43d332bcafe1fdbf6534aea63650 -->
```
        <source>Copy transaction ID and output index</source>
        <translation>거래  결과 인덱스값 혹은 ID 복사</translation>
    
ERR
The translation inaccurately splits the phrase and changes the meaning. The source specifies copying both the transaction ID and the output index, but the translation suggests copying either the output index or the ID, which is incorrect. Also, the spacing between "거래" and "결과" is unnecessary, and "거래 결과" is not the right term for "transaction output."

Correct translation:
트랜잭션 ID와 출력 인덱스를 복사
```

<!-- cache_translation_check_ko_00080d4ce4216092eb37238cbaab151b5229e65e98c532d197f035146472a551 -->
```
        <source>Unlock unspent</source>
        <translation> 사용 안 함 잠금 해제</translation>
    
ERR
There is a whitespace formatting issue: there is an unnecessary space at the start of the translation. Additionally, the translation is somewhat awkward and unnatural in Korean. The English phrase "Unlock unspent" means to unlock previously locked unspent transaction outputs. A more accurate and natural translation would be:

Correct translation:
언스펜트 잠금 해제

Or, more clearly:
잠금 해제되지 않은 금액 해제

But the most direct and relevant in the Bitcoin context is:
미사용(언스펜트) 잠금 해제

So, the answer:

ERR
There is an unnecessary space at the start, and the translation is awkward. A better translation would be:
미사용(언스펜트) 잠금 해제
```

<!-- cache_translation_check_ko_c23af664e4befdb041e6131901acaeb1b5199f5166201e068358ec2a7946444a -->
```
        <source>Migrating the wallet will convert this wallet to one or more descriptor wallets. A new wallet backup will need to be made.
If this wallet contains any watchonly scripts, a new wallet will be created which contains those watchonly scripts.
If this wallet contains any solvable but not watched scripts, a different and new wallet will be created which contains those scripts.

The migration process will create a backup of the wallet before migrating. This backup file will be named &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak and can be found in the directory for this wallet. In the event of an incorrect migration, the backup can be restored with the "Restore Wallet" functionality.</source>
        <translation>지갑을 마이그레이션하면 이 지갑은 하나 이상의 설명자 지갑으로 변환됩니다. 새로운 지갑 백업이 필요합니다. 이 지갑에 watchonly 스크립트가 포함되어 있으면, 해당 watchonly 스크립트를 포함하는 새로운 지갑이 생성됩니다. 해결 가능하지만 관찰되지 않은 스크립트가 포함되어 있으면, 해당 스크립트를 포함하는 다른 새로운 지갑이 생성됩니다.

마이그레이션 과정은 마이그레이션 전에 지갑 백업을 생성합니다. 이 백업 파일은 -.legacy.bak로 명명되며 이 지갑의 디렉토리에서 찾을 수 있습니다. 마이그레이션이 잘못될 경우, '지갑 복원' 기능을 통해 백업을 복원할 수 있습니다.</translation>
    
ERR
The translation omits the format specifiers "<wallet name>" and "<timestamp>", simply stating "-.legacy.bak" without indicating the placeholders for the wallet name and timestamp as in the original. This could result in a loss of important information for the user. Also, the quoted phrase "Restore Wallet" in the last sentence should ideally remain in English as in the source, unless there is a specifically localized UI string.

Correct translation:
지갑을 마이그레이션하면 이 지갑은 하나 이상의 설명자 지갑으로 변환됩니다. 새로운 지갑 백업을 만들어야 합니다.
이 지갑에 watchonly 스크립트가 포함되어 있다면, 해당 watchonly 스크립트를 포함하는 새로운 지갑이 생성됩니다.
해결 가능하지만 관찰되지 않은 스크립트가 포함되어 있다면, 해당 스크립트를 포함하는 다른 새로운 지갑이 생성됩니다.

마이그레이션 과정에서는 마이그레이션 전에 지갑의 백업을 생성합니다. 이 백업 파일은 &lt;지갑 이름&gt;-&lt;타임스탬프&gt;.legacy.bak로 명명되며, 이 지갑의 디렉토리에서 찾을 수 있습니다.
마이그레이션이 잘못된 경우 "Restore Wallet" 기능을 사용하여 백업을 복원할 수 있습니다.
```

<!-- cache_translation_check_ko_29d217922568a7fe2d7c1db68b5542a8193cfb9fc21b36ad8185c5db3fb7800e -->
```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>외부 서명 지원 없이 컴파일됨 (외부 서명에 필요) 개발자 참고 사항 [from:developer] "외부 서명"은 하드웨어 지갑과 같은 장치를 사용하는 것을 의미합니다.</translation>
    
ERR
The translation includes an extra explanation ("개발자 참고 사항 [from:developer] "외부 서명"은 하드웨어 지갑과 같은 장치를 사용하는 것을 의미합니다.") that should not be present in the translation string intended for the main UI. The explanation belongs to the comment, not the actual translation.

Correct translation:
외부 서명 지원 없이 컴파일되었습니다(외부 서명에 필요함)

If needed, you can also say:
외부 서명 지원 없이 컴파일됨(외부 서명에 필요함)
```

<!-- cache_translation_check_ko_9f7d25d0c2cc99b69551750d75636ec648cbda0fdde9d389c65ee7cef9aea4c4 -->
```
        <source>The label associated with this address list entry</source>
        <translation>현재 선택된 주소 필드의 라벨입니다.</translation>
    
ERR
The translation is inaccurate. The source means "The label associated with this address list entry," but the translation states "The label of the currently selected address field," which changes the meaning.

Correct translation:
이 주소 목록 항목과 연결된 라벨입니다.
```

<!-- cache_translation_check_ko_b27619587b78cfc5f2e7dc94f9a28085204224a69924b8f936fb73e017c70fc7 -->
```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>본 주소록 입력은 주소와 연계되었습니다.  이것은 보내는 주소들을 위해서만 변경될수 있습니다.</translation>
    
ERR
There are several issues:
1. The translation contains awkward phrasing ("본 주소록 입력은 주소와 연계되었습니다") which does not clearly convey "The address associated with this address list entry".
2. There is double spacing ("연계되었습니다.  이것은").
3. More natural Korean wording and proper spacing/grammar are needed for clarity.

Correct translation:
이 주소록 항목에 연결된 주소입니다. 이 주소는 보내는 주소에 대해서만 수정할 수 있습니다.
```

<!-- cache_translation_check_ko_0e9655f99e118f8a54a25af4cdeff393810e8a953906cf2aaa6d4bcd618aca3e -->
```
        <source>Number of script verification threads</source>
        <translation>스크립트 인증 쓰레드의 개수(V)</translation>
    
ERR
The translation includes an unexplained "(V)" at the end, which is not present in the source text and may confuse users. Also, "인증" is better translated as "검증" (meaning "verification") in the context of "script verification" in Bitcoin.

Correct translation:
스크립트 검증 스레드 수
```

<!-- cache_translation_check_ko_2a769584874febba5f0573486704f95d97ae24e4df6e096116c3b7b2ecfb590e -->
```
        <source>Set the number of script verification threads. Negative values correspond to the number of cores you want to leave free to the system.</source>
        <extracomment>Tooltip text for Options window setting that sets the number of script verification threads. Explains that negative values mean to leave these many cores free to the system.</extracomment>
        <translation>스크립트 검증 수명의 숫자를 설정하세요. 음수는 시스템에 묶이지 않는 자유로운 코어의 수를 뜻합니다.</translation>
    
ERR
The translation is inaccurate and somewhat misleading. "스크립트 검증 수명" means "script verification lifespan", which is incorrect. The original means "the number of script verification threads", not lifespan. Also, "묶이지 않는 자유로운 코어" is awkward and doesn't clearly convey the meaning of "leave these many cores free to the system".

Correct translation:
스크립트 검증 스레드 수를 설정합니다. 음수 값은 시스템에 남길 코어의 수를 의미합니다.
```

<!-- cache_translation_check_ko_24da5e7ffd0d17fe3ea7dd162a24b7998a1b8dc8a877b5cafcb4162aa83c53c8 -->
```
        <source>Whether to set subtract fee from amount as default or not.</source>
        <extracomment>Tooltip text for Options window setting that sets subtracting the fee from a sending amount as default.</extracomment>
        <translation>수수료 감면을 초기값으로 할지 혹은 설정하지 않을지를 결정합니다.</translation>
    
ERR
The translation is not accurate. "수수료 감면" means "fee reduction", not "subtracting the fee from the amount". Also, the meaning of setting it as default is not clearly conveyed.

Correct translation:
수수료를 금액에서 차감하는 것을 기본값으로 설정할지 여부입니다.
```

<!-- cache_translation_check_ko_ed2eb1c02e1f4c3a6b194fdd8c9c3ebe7f82afc79e7a3062d3d81cd0c5135b93 -->
```
        <source>Spend unconfirmed change</source>
        <translation>검증되지 않은 잔돈 쓰기 (S)</translation>
    
ERR
The translation "검증되지 않은 잔돈 쓰기 (S)" is understandable but contains a few issues:
1. "검증되지 않은" is closer to "unverified" than "unconfirmed" (which is more commonly "확인되지 않은" in the context of Bitcoin).
2. The "(S)" at the end does not correspond to anything in the source; it appears to be extraneous.
3. The tone "쓰기" (to write) is odd in context; "사용" (use/spend) or "지출" (spend) is more natural in financial and Bitcoin-related contexts.

Correct translation:
확인되지 않은 잔돈 사용

Or, more literally:
확인되지 않은 잔돈 지출
```

<!-- cache_translation_check_ko_9ec848049a006597f2ebab1d4e0ae0c35ae20ea65473b45014cb037c17430e4e -->
```
        <source>External signer script path</source>
        <translation>외부 서명자 스크립트 경로
 </translation>
    
ERR
There is a trailing whitespace/newline after the translation, which introduces unwanted formatting. The translation itself is accurate.

Correct translation:
외부 서명자 스크립트 경로
```

<!-- cache_translation_check_ko_40ff9310190a62ff8a34420ba52f86bcae749cdba300bfb66a64faaea43c235e -->
```
        <source>Connect through SOCKS5 proxy (default proxy):</source>
        <translation>SOCKS5 프록시를 거쳐 연결합니다(C) (기본 프록시):</translation>
    
ERR
The translation adds "(C)" which is not present in the source and may be a mistaken accelerator or extraneous content. Otherwise, the translation is correct, but the addition is unwanted.

Correct translation:
SOCKS5 프록시를 통해 연결합니다 (기본 프록시):
```

<!-- cache_translation_check_ko_137742af9986be43f2ea160cba916358fdb98aad73fe8235f106423ba64deece -->
```
        <source>Show the icon in the system tray.</source>
        <translation>시스템 트레이에 있는 아이콘 숨기기</translation>
    
ERR
The translation is incorrect. The source says "Show the icon in the system tray," but the Korean translation means "Hide the icon in the system tray." The meaning is the opposite.

Correct translation:
시스템 트레이에 아이콘을 표시하기
```

<!-- cache_translation_check_ko_d167e5369c4628a577dddb98eda03c78f8ee19983e3c6ad75a30ab2829845bfa -->
```
        <source>Third-party URLs (e.g. a block explorer) that appear in the transactions tab as context menu items. %s in the URL is replaced by transaction hash. Multiple URLs are separated by vertical bar |.</source>
        <translation>내용 메뉴 아이템으로 거래내역 탭이 보이는 제3자 URL (블록익스프로러). URL에 %s는 트랜잭션 해시값으로 대체됩니다. 복수의 URL은 수직항목으로부터 분리됩니다. </translation>
    
ERR
There are several issues in the translation:
- "내용 메뉴 아이템으로 거래내역 탭이 보이는 제3자 URL (블록익스프로러)." is awkward and unclear. It does not clearly state that the URLs appear as context menu items in the transactions tab.
- "블록익스프로러" should be "블록 탐색기" for natural Korean.
- "복수의 URL은 수직항목으로부터 분리됩니다." is a mistranslation of "Multiple URLs are separated by vertical bar |.". It should directly mention "vertical bar (|)" in the explanation rather than translating to "수직항목".
- The translation omits or mistranslates the explanation about the substitution of %s in the URL.

Correct translation:
거래 탭의 컨텍스트 메뉴 항목으로 표시되는 제3자 URL(예: 블록 탐색기)입니다. URL의 %s는 트랜잭션 해시로 대체됩니다. 여러 개의 URL은 수직 막대(|)로 구분합니다.
```

<!-- cache_translation_check_ko_29d217922568a7fe2d7c1db68b5542a8193cfb9fc21b36ad8185c5db3fb7800e -->
```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>외부 서명 지원 없이 컴파일됨 (외부 서명에 필요) 개발자 참고 사항 [from:developer] "외부 서명"은 하드웨어 지갑과 같은 장치를 사용하는 것을 의미합니다.</translation>
    
ERR
The translation includes an extra explanation ("개발자 참고 사항 [from:developer] "외부 서명"은 하드웨어 지갑과 같은 장치를 사용하는 것을 의미합니다.") that should not be present in the translation string intended for the main UI. The explanation belongs to the comment, not the actual translation.

Correct translation:
외부 서명 지원 없이 컴파일되었습니다(외부 서명에 필요함)

If needed, you can also say:
외부 서명 지원 없이 컴파일됨(외부 서명에 필요함)
```

<!-- cache_translation_check_ko_c1ea82977e90ea4020d9d9e7a3fc2a2401a05ff8b5377cd0b9beeea255ac1404 -->
```
        <source>Address Relay</source>
        <extracomment>Text title for the Address Relay field in the peer details area, which displays whether we relay addresses to this peer (Yes/No).</extracomment>
        <translation>지갑주소를 릴레이합니다.</translation>
    
ERR
The translation "지갑주소를 릴레이합니다." means "We relay wallet addresses.", which is not accurate as a field label or title. The original English "Address Relay" is a short noun phrase, likely intended as a label or section title, not a full sentence. Additionally, "지갑주소" (wallet address) may be too specific; just "주소" (address) likely fits better.

Correct translation:
주소 릴레이
```

<!-- cache_translation_check_ko_42205772398742f09b157a30b3ca0fcd565e9ac2444d5829427bc7fe551dbbfb -->
```
        <source>Addresses Processed</source>
        <extracomment>Text title for the Addresses Processed field in the peer details area, which displays the total number of addresses received from this peer that were processed (excludes addresses that were dropped due to rate-limiting).</extracomment>
        <translation>처리된 지갑</translation>
    
ERR
The translation of "Addresses Processed" as "처리된 지갑" is incorrect. "지갑" means "wallet," which does not accurately reflect "addresses." The correct term should refer to "addresses," not "wallets."

Correct translation:
처리된 주소
```

<!-- cache_translation_check_ko_822541b62cbc56a76fb81cddee217251f0d8f70399d19b37e3f86e5ef81f19ac -->
```
        <source>Addresses Rate-Limited</source>
        <extracomment>Text title for the Addresses Rate-Limited field in the peer details area, which displays the total number of addresses received from this peer that were dropped (not processed) due to rate-limiting.</extracomment>
        <translation>지갑의 Rate제한</translation>
    
ERR
The translation is inaccurate. "Addresses Rate-Limited" refers to addresses that have been subject to rate limiting, not specifically wallets ("지갑"). Also, "Rate제한" is a partial translation and unnatural in Korean.

Correct translation:
주소가 속도 제한됨
```

<!-- cache_translation_check_ko_83ad4efcd8ffef05a3701c2d64f7b04f0bb9d1b68b35d80ebf705aff45fe737e -->
```
        <source>Inbound: initiated by peer</source>
        <extracomment>Explanatory text for an inbound peer connection.</extracomment>
        <translation>시작점 : 동기에 의해 시작됨</translation>
    
ERR
The translation is inaccurate. "Inbound" refers to an incoming connection, and "initiated by peer" means the connection was started by the remote peer. The translation "시작점 : 동기에 의해 시작됨" incorrectly uses "시작점" (starting point) and "동기" (motivation/synchronization), which are not accurate in the context of network connections.

Correct translation:
수신: 피어에 의해 시작됨
```

<!-- cache_translation_check_ko_4789040303c7928d2fc8941a376b6155250adee48a6205f177e0f9d2cbf9e131 -->
```
        <source>Outbound Manual: added using RPC %1 or %2/%3 configuration options</source>
        <extracomment>Explanatory text for an outbound peer connection that was established manually through one of several methods. The numbered arguments are stand-ins for the methods available to establish manual connections.</extracomment>
        <translation>아웃바운드 매뉴얼 : RPC %1 이나 %2/%3 을 사용해서 환경설정 옵션을 추가</translation>
    
ERR
The translation contains spacing issues (there is a space before the colon, which is not standard Korean punctuation usage), and the end of the sentence is unnatural. The part "환경설정 옵션을 추가" is an incomplete expression; it should be "환경설정 옵션을 사용하여 추가됨" or similar to match the passive nuance ("added using... options").

Correct translation:
아웃바운드 수동 연결: RPC %1 또는 %2/%3 설정 옵션을 사용하여 추가됨
```

<!-- cache_translation_check_ko_e219d8699d3c29f415479681efc99b55081f6cd5b2ec053a216edb324c48f6b7 -->
```
        <source>Copy label</source>
        <translation>복사  라벨</translation>
    
ERR
The translation uses incorrect word order and has an unnecessary double space. In Korean, the correct expression is "라벨 복사" or "라벨 복사하기".

Correct translation:
라벨 복사
```

<!-- cache_translation_check_ko_553628ad7aed874e5e6253d971ebfd31eab43c2b6cc3ce82f25f7faa5b449faa -->
```
        <source>Copy amount</source>
        <translation>복사  금액</translation>
    
ERR
There is an unnecessary space between "복사" and "금액", which creates a formatting issue. The correct translation should be:

Correct translation:
금액 복사
```

<!-- cache_translation_check_ko_95816f890e58123dad4be944a36724ff5115fc7dedcd5cbde31b51b71a632ef8 -->
```
        <source>Request payment to …</source>
        <translation>에게 지불을 요청</translation>
    
ERR
The translation is incomplete and lacks the subject or recipient of the request. The ellipsis "…" is also missing, and the phrase is unnatural in Korean.

Correct translation:
…에게 결제를 요청
or
…에게 결제 요청

The ellipsis should be maintained for context.
```

<!-- cache_translation_check_ko_f516145b6949c0abeeadb18e9e377e82cd2c7a0741b0e82976d9435cdc5afc07 -->
```
        <source>Custom change address</source>
        <translation>주소 변경</translation>
    
ERR
The translation "주소 변경" means "change address" as in "to change an address", not "custom change address" (where "change address" refers to a specific kind of address for Bitcoin transaction change outputs). This translation could be misleading in the Bitcoin context.

Correct translation:
사용자 지정 잔돈 주소
```

<!-- cache_translation_check_ko_2ea14ca6a819de6dd59530fe417145eb6a88c1b15e4693f572641c6ec4418d45 -->
```
        <source>Create Unsigned</source>
        <translation>사인되지 않은 것을 생성(e)</translation>
    
ERR
The translation "사인되지 않은 것을 생성(e)" is awkward and the use of "(e)" is not standard in Korean. "Unsigned" in the context of Bitcoin usually refers to an "unsigned transaction". A more natural and accurate translation would be:

Correct translation:
서명되지 않은 것 생성

Alternatively, if the context is about creating an unsigned transaction, it could be:
서명되지 않음을 생성

But most generally:
서명되지 않은 것 생성

The parentheses and the "e" should be removed.
```

<!-- cache_translation_check_ko_db67116095ecb3e270353f2bf0405dd11063e88d541006b1fdcbca498b282286 -->
```
        <source>Not signalling Replace-By-Fee, BIP-125.</source>
        <translation>'수수료로-대체', BIP-125를 지원하지 않습니다.</translation>
    
ERR
The translation misinterprets the source. The English "Not signalling Replace-By-Fee, BIP-125." means it is not indicating (not signaling) Replace-By-Fee (RBF) per BIP-125, not that it does not support it. The Korean translation "'수수료로-대체', BIP-125를 지원하지 않습니다." states "does not support," which changes the meaning.

Correct translation:
Replace-By-Fee, BIP-125를 신호하지 않습니다.
Or (more naturally):
Replace-By-Fee(수수료로-대체), BIP-125를 신호하지 않습니다.
```

<!-- cache_translation_check_ko_d07b5c101eb15757763e2c277765b6c96a77b6c28054e4803610cf0571fd010e -->
```
        <source>Warning: Unknown change address</source>
        <translation>경고: 알려지지 않은 주소 변경입니다</translation>
    
ERR
The translation is inaccurate. "알려지지 않은 주소 변경입니다" means "Unknown address change," not "Unknown change address." In the Bitcoin context, "change address" refers to the address that will receive the change from a transaction, not to a changed address.

Correct translation:
경고: 알 수 없는 잔돈 주소입니다
```

<!-- cache_translation_check_ko_1d1f8af7ad9d848e5ad2f3ba602c5bb5272921e21289e76d61d61781fe7f717a -->
```
        <source>Subtract fee from amount</source>
        <translation>송금액에서 수수료 공제(U)</translation>
    
ERR
The translation adds "(U)", which is not present in the original English text. Unless "(U)" is a required UI hotkey or convention in the application, it constitutes an erroneous addition. If "(U)" is not required, it should be omitted.

Correct translation:
송금액에서 수수료 공제
```

<!-- cache_translation_check_ko_841ade80b544ef394decfc9b7112bd8f00b76cd9b362bf66fa1a6839d27601ac -->
```
        <source>Received with</source>
        <translation>받은 주소 :</translation>
    
ERR
The translation "받은 주소 :" means "Received address:" which is overly specific and introduces an extra colon not present in the source. The original phrase "Received with" is ambiguous and is often completed by a label or method (e.g., "Received with [address/label]"). The translation should reflect this ambiguity.

Correct translation:
받은 항목

Or, if contextually used in Bitcoin wallet as "Received with [address/label]", a more accurate translation would be:
다음으로 받은

But, for strict literal translation:
받은 곳

No colon should be appended.
```

<!-- cache_translation_check_ko_f13c9375c48024a1c170311452a4087bce7170e8df021381eb21c766deb37b76 -->
```
        <source>Received from</source>
        <translation>보낸 주소 :</translation>
    
ERR
The translation is incorrect. "보낸 주소" means "Sent address" or "Sender address", not "Received from". It reverses the meaning and could be misleading.

Correct translation:
받은 주소 :
or simply
받은 곳 :
or
받은 사람 :

Choose depending on UI context, but all are better than the original.
```

<!-- cache_translation_check_ko_841ade80b544ef394decfc9b7112bd8f00b76cd9b362bf66fa1a6839d27601ac -->
```
        <source>Received with</source>
        <translation>받은 주소 :</translation>
    
ERR
The translation "받은 주소 :" means "Received address:" which is overly specific and introduces an extra colon not present in the source. The original phrase "Received with" is ambiguous and is often completed by a label or method (e.g., "Received with [address/label]"). The translation should reflect this ambiguity.

Correct translation:
받은 항목

Or, if contextually used in Bitcoin wallet as "Received with [address/label]", a more accurate translation would be:
다음으로 받은

But, for strict literal translation:
받은 곳

No colon should be appended.
```

<!-- cache_translation_check_ko_e219d8699d3c29f415479681efc99b55081f6cd5b2ec053a216edb324c48f6b7 -->
```
        <source>Copy label</source>
        <translation>복사  라벨</translation>
    
ERR
The translation uses incorrect word order and has an unnecessary double space. In Korean, the correct expression is "라벨 복사" or "라벨 복사하기".

Correct translation:
라벨 복사
```

<!-- cache_translation_check_ko_553628ad7aed874e5e6253d971ebfd31eab43c2b6cc3ce82f25f7faa5b449faa -->
```
        <source>Copy amount</source>
        <translation>복사  금액</translation>
    
ERR
There is an unnecessary space between "복사" and "금액", which creates a formatting issue. The correct translation should be:

Correct translation:
금액 복사
```

<!-- cache_translation_check_ko_f2a51449e62d374f3728e6b435b991e04f5fd19657588340195fa598913286f2 -->
```
        <source>Copy transaction ID</source>
        <translation>복사 트랜잭션  아이디</translation>
    
ERR
The word order is unnatural in Korean, and there is an unnecessary double space between "트랜잭션" and "아이디". The correct translation should be:

트랜잭션 아이디 복사

This is more natural and properly reflects the English source.
```

<!-- cache_translation_check_ko_71062a71cd42146a3f3bbab443a266ed4fa29c79ebe8b0f46f3cc8c6d01ecf5e -->
```
        <source>%s corrupt. Try using the wallet tool bitcoin-wallet to salvage or restoring a backup.</source>
        <translation>%s가 손상되었습니다. '비트 코인-지갑'을 사용하여 백업을 구제하거나 복원하십시오.</translation>
    
ERR
There are several issues in the translation:
1. The tool name "bitcoin-wallet" is mistranslated as "비트 코인-지갑", but it should be kept as the command-line tool name in English for clarity to users.
2. The phrase "to salvage or restoring a backup." is mistranslated. The word "salvage" is best translated as "복구" whereas "restore" as "복원", but the sentence suggests using the tool to salvage or to restore a backup -- which needs to be clear.
3. The format specifier %s is correctly retained.

Correct translation:
%s가 손상되었습니다. bitcoin-wallet 도구를 사용하여 복구하거나 백업을 복원해 보십시오.
```

<!-- cache_translation_check_ko_49a8f73792fe8ea4b6dfde6da29a15203449d6295acf8ac11f93258135a16845 -->
```
        <source>Cannot upgrade a non HD split wallet from version %i to version %i without upgrading to support pre-split keypool. Please use version %i or no version specified.</source>
        <translation>사전분리 키풀를 지원하기 위해서 업그레이드 하지 않고는 Non HD split 지갑의 %i버젼을 %i버젼으로 업그레이드 할 수 없습니다. %i버젼을 활용하거나 구체화되지 않은 버젼을 활용하세요.</translation>
    
ERR
There are several issues with the translation:
- "Non HD split" should be written as "HD로 분리되지 않은" or "비 HD 분할".
- The grammatical structure is misleading; the original explains that you cannot upgrade *without* a certain step, but the Korean translation confuses the logical order.
- "키풀를" should be "키풀을".
- The phrase "버젼" should be "버전".
- "구체화되지 않은 버젼" is an awkward translation for "no version specified".

Correct translation:
HD로 분리되지 않은 지갑을 사전분리 키풀 지원 없이 버전 %i에서 버전 %i로 업그레이드할 수 없습니다. 버전 %i 또는 버전을 지정하지 않고 사용하세요.
```

<!-- cache_translation_check_ko_1e0ad7e7393ababbf21dbe2ef92d9cebd95df7db9cfbb043a1f616e9c02d1f65 -->
```
        <source>Invalid or corrupt peers.dat (%s). If you believe this is a bug, please report it to %s. As a workaround, you can move the file (%s) out of the way (rename, move, or delete) to have a new one created on the next start.</source>
        <translation>유효하지 않거나 손상된 peers.dat(%s). 만약 이게 버그인 경우에, %s이쪽으로 리포트해주세요.  새로 만들어서 시작하기 위한 해결방법으로 %s파일을 옮길 수 있습니다. (이름 재설정, 파일 옮기기 혹은 삭제).</translation>
    
ERR
There are several issues with the translation:
- "%s이쪽으로 리포트해주세요" is awkward Korean; the postposition "이쪽으로" is not natural, and "리포트" is Konglish—"보고" or "신고해 주세요" is better.
- The sentence segmentation does not match the original; also, the use of "새로 만들어서 시작하기 위한 해결방법으로 %s파일을 옮길 수 있습니다." is unnatural and doesn't correctly convey "as a workaround".
- The translation omits some of the original's options (rename, move, or delete), which are not fully reflected as alternatives.
- There are spacing issues (e.g., "%s파일" should be "%s 파일").
- The overall register and readability can be much improved.

Correct translation:
유효하지 않거나 손상된 peers.dat(%s) 파일입니다. 이것이 버그라고 생각되면 %s로 보고해 주세요. 임시 방편으로, 해당 파일(%s)을 다른 위치로 옮기거나 (이름 변경, 이동, 또는 삭제) 다음 시작 시 새 파일이 생성되도록 할 수 있습니다.
```

<!-- cache_translation_check_ko_0dba87d5161c4fa7668150ae5a7933b3046bab1d5bd5834f23cdd0683cd0e9bb -->
```
        <source>No wallet file format provided. To use createfromdump, -format=&lt;format&gt; must be provided.</source>
        <translation>shshhdchb bdfjj fb  rciivfjb doffbfbdjdj</translation>
    
SPAM
The translation consists of unrelated gibberish and does not correspond to the provided English source.

Correct translation:
지갑 파일 형식이 제공되지 않았습니다. createfromdump을 사용하려면 -format=&lt;형식&gt;을 제공해야 합니다.
```

<!-- cache_translation_check_ko_cf4d336bc66070a03acf58727670a1e7f0972777d7f45c8b933b76baec983b25 -->
```
        <source>Cannot set -forcednsseed to true when setting -dnsseed to false.</source>
        <translation>naravfbj. dufb jdncnlfs. jx dhcji djc d jcbc jdnbfbicb </translation>
    
SPAM
The provided 'ko' translation consists of nonsensical and unrelated text, not Korean language. It looks like random gibberish.

Correct translation:
-dnsseed를 false로 설정할 때 -forcednsseed를 true로 설정할 수 없습니다.
```

<!-- cache_translation_check_ko_3be6f3fbb026285eb89ed70715d8baa12cfa3d198679f2a871a8ab935a59c5fc -->
```
        <source>Dump file %s does not exist.</source>
        <translation>파일 버리기 %s 존재 안함</translation>
    
ERR
The Korean translation is awkward and ungrammatical. "파일 버리기 %s 존재 안함" literally means "File dumping %s does not exist," but is phrased in a non-standard way and uses improper grammar. A more natural Korean translation would be:

Correct translation:
덤프 파일 %s이(가) 존재하지 않습니다.
```

<!-- cache_translation_check_ko_5c873a36508f0b4d4557c4b87fc7122002176cd08cba40bf8e7f24c57ac51457 -->
```
        <source>Error creating %s</source>
        <translation>만들기 오류 %s</translation>
    
ERR
The Korean translation is unnatural and does not accurately reflect the English structure. It literally says "creation error %s," which is awkward in Korean. The correct form should place the error at the front, matching natural Korean error reporting conventions.

Correct translation:
%s 생성 오류
```

<!-- cache_translation_check_ko_9163f1d732e3d28d5a52e740832040a9e744af97bcb24c84bb2ebac8868972e0 -->
```
        <source>Failed to verify database</source>
        <translation>데이터베이스를 검증 실패</translation>
    
ERR
The Korean translation is grammatically incorrect. The phrase "데이터베이스를 검증 실패" is missing a verb or linking phrase, making it awkward and ungrammatical. A correct translation would be:

Correct translation:
데이터베이스 검증에 실패했습니다.
```

<!-- cache_translation_check_ko_65fd42f25dd666c446ea8979c14d3fb18c3f1dc5774ca8919a7cd80f5cd60fc8 -->
```
        <source>Invalid netmask specified in -whitelist: '%s'</source>
        <translation>유효하지 않은 넷마스크가 -whitelist: '%s" 를 통해 지정됨</translation>
    
ERR
There is a quotation mark inconsistency: the source uses '%s' but the translation has '%s". Also, spacing is slightly off.

Correct translation:
유효하지 않은 넷마스크가 -whitelist: '%s'에 지정되었습니다.
```

<!-- cache_translation_check_ko_a3b1bb020f4c323d4fb3162a75b7657e1443b68a8364c9158a3568441f916c40 -->
```
        <source>SQLiteDatabase: Failed to read database verification error: %s</source>
        <translation>에스큐엘라이트 데이터베이스 : 데이터베이스 읽기를 실패하였습니다: %s</translation>
    
ERR
The translation is inaccurate. The original message is "Failed to read database verification error," meaning it failed to read a verification error from the database, not that it failed to read the database. Also, there should not be a space before the colon, and "에스큐엘라이트 데이터베이스" is verbose and not standard for "SQLiteDatabase" in Korean UI text.

Correct translation:
SQLiteDatabase: 데이터베이스 검증 오류를 읽는 데 실패했습니다: %s
```

<!-- cache_translation_check_ko_55021f269ff8a83e3353c1d37634fdcf22180aff51e66735caa5f80efc5b74f2 -->
```
        <source>Transaction amounts must not be negative</source>
        <translation>거래액은 반드시 0보다 큰 값이어야 합니다.</translation>
    
ERR
The translation is inaccurate. The English source states that transaction amounts "must not be negative," meaning they can be zero or positive. The Korean translation, however, insists that the amount "must be greater than 0" (즉, 0보다 커야 함), which excludes zero and changes the meaning.

Correct translation:
거래 금액은 음수일 수 없습니다.
```

<!-- cache_translation_check_ko_523bed98aff409ddaac231d35b5652631ff03668c0f50999ff193e25706b1090 -->
```
        <source>Unknown -blockfilterindex value %s.</source>
        <translation>알 수 없는 -blockfileterindex 값 %s.</translation>
    
ERR
There is a typo in the option: '-blockfileterindex' should be '-blockfilterindex'. Otherwise, the translation is accurate.

Correct translation:
알 수 없는 -blockfilterindex 값 %s.
```
</details>

Number of issues: 54.
