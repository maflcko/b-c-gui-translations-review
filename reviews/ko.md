# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>ko</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bko%5D%20request)


<!-- cache_translation_check_ko_0dbcd54a09f4610a9e1587214c50edd10fe31b05d4084e8abcc04eacb9d0306b -->
```
        <source>C&amp;lose</source>
        <translation>C&amp;닫기</translation>
    
ERR
The translation incorrectly includes an extra Latin "C" before the ampersand ("C&닫기"). The source's ampersand should appear exactly once as the mnemonic marker, and the translated label should not contain the extraneous "C".

Correct translation:
&닫기
```

<!-- cache_translation_check_ko_743dc2ba81b3c015a9b142097624bfe2847180f2917ac7d28cab788ac3f6687c -->
```
        <source>Delete the currently selected address from the list</source>
        <translation>목록에 현재 선택한 주소 삭제</translation>
    
ERR
The Korean is a fragment and uses the wrong particle ("목록에" should be "목록에서") and lacks a proper verb ending for clarity. Better translations:

- Formal/complete: "목록에서 현재 선택된 주소를 삭제합니다"
- Short UI label: "목록에서 선택한 주소 삭제"
```

<!-- cache_translation_check_ko_ccc252e47f1f77bfb0cf0f871052e6a0bed43281f97d6eaa52a55d21e24113f2 -->
```
        <source>C&amp;hoose</source>
        <translation>선택(&amp;H)</translation>
    
ERR
The shortcut key '&' should match the position and character in the translation. In Korean UI, it's customary to use the first consonant/letter after the translated word, aligning with the shortcut key from the English source if possible. Here, 'C&amp;hoose' should ideally map to '선택(&amp;C)' (matching the C) or '선택(&amp;S)' (for the Korean), but matching the H from the English "Choose" is not appropriate as it doesn't match the Korean word.

Correct translation:
선택(&amp;C)
```

<!-- cache_translation_check_ko_e14a0181241f036d680a3cc9973aabc089321ba260f1ea8060b5beed4b631922 -->
```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>지갑 암호화 해제를 위해 입력된 비밀문구가 정확하지 않습니다. 비밀문구가 공백 문자 (0 바이트)를 포함하고 있습니다. 만약 비밀문구가 25.0 버전 이전의 비트코인 코어 소프트웨어에 의해 설정되었다면, 비밀문구를 첫 공백 문자 이전까지 입력해보세요. 이렇게 해서 성공적으로 입력되었다면, 차후 이런 문제가 발생하지 않도록 비밀문구를 새로이 설정해 주세요.</translation>
    
ERR
The translation incorrectly interprets "null character (ie - a zero byte)" as "공백 문자 (0 바이트)", which means "whitespace character (0 bytes)". In computing, a "null character" is "널 문자" in Korean, and it is not the same as a whitespace character. The rest of the translation is otherwise accurate, but this is a semantic error that could lead to misunderstanding.

Correct translation:
지갑 암호 해제를 위해 입력한 비밀번호가 올바르지 않습니다. 비밀번호에 널 문자(즉, 0 바이트)가 포함되어 있습니다. 만약 이 비밀번호가 25.0 이전 버전의 비트코인 코어 소프트웨어에서 설정된 것이라면, 첫 번째 널 문자까지만(첫 번째 널 문자를 포함하지 않고) 입력해 보세요. 이렇게 해서 성공했다면, 이러한 문제가 다시 발생하지 않도록 새 비밀번호를 설정해 주세요.
```

<!-- cache_translation_check_ko_5160cfb5fc4e2897cfb4de6ceabd301a4a04cb65c29bc6e9358ad17efee0f634 -->
```
        <source>Custom…</source>
        <translation>사용자정의</translation>
    
ERR
Problems:
- Missing ellipsis (…) that indicates a continuation in the UI.
- Missing space between words; "사용자정의" should be "사용자 정의" (or "사용자 지정" depending on meaning).

Correct translations (choose as appropriate for context):
- 사용자 정의…
- 사용자 지정…
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

<!-- cache_translation_check_ko_f5706b433938f3308c5ad5e321e23bfed7a55d70692bef8dfa89f39b699b488e -->
```
        <source>Load PSBT from &amp;clipboard…</source>
        <translation>PSBT 혹은 클립보드에서 불러오기</translation>
    
ERR
The translation omits the format and position of "&" for the shortcut, and slightly changes the meaning. The original means "Load PSBT from clipboard", but the translation says, "Load PSBT or from clipboard", which introduces ambiguity. Also, the shortcut (&) is missing.

Correct translation:
클립보드에서 PSBT 불러오기(&C)…
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

<!-- cache_translation_check_ko_5a4ba9676d667edc9e3b187ef6c9aaa2aadab5a13e82e772f5480a9cc0375f97 -->
```
        <source>Copy &amp;label</source>
        <translation>복사 &amp; 라벨</translation>
    
ERR
There is an unnecessary space between '&amp;' and '라벨' in the Korean translation. Shortcut keys should not have a space after '&'. Also, the word order is unnatural in Korean—it should be '라벨(&amp;L) 복사' or '라벨 복사(&amp;L)' if the shortcut is L, or at least '&amp;라벨 복사' if the '&' must be placed at the start.

Correct translation:
라벨(&amp;L) 복사
or
라벨 복사(&amp;L)
```

<!-- cache_translation_check_ko_89bd2f8f56e8e2bc841f5999c311ab74b07e2ba7aac385043317dc4c2b862e7a -->
```
        <source>Copy &amp;amount</source>
        <translation>복사 &amp; 금액</translation>
    
ERR
There is an unnecessary space between "복사" and "금액," which is not natural in Korean. The shortcut key (&) is preserved correctly, but the spacing should be fixed.

Correct translation:
복사(&amp;A) 금액

However, if aligning with the source order, "금액 복사(&amp;A)" would be most natural, but the shortcut key should match the original if possible. If the ampersand is to stay with "amount," then:

금액(&amp;A) 복사

Choose one that matches the actual software context, but remove the extra space.
```

<!-- cache_translation_check_ko_f89690f24f73e7a4058b35073a41fbf2e7fbf2ee71cc39c86029542369d50dd2 -->
```
        <source>Copy transaction &amp;ID and output index</source>
        <translation>거래 &amp; 결과 인덱스값 혹은 ID 복사</translation>
    
ERR
The translation is inaccurate. The Korean text can be interpreted as "Copy transaction &amp; result index value or ID," which is not faithful to the original intent of "Copy transaction &amp;ID and output index." Both the transaction ID and the output index need to be copied together, not one or the other.

Correct translation:
거래 &amp;ID와 출력 인덱스 복사
```

<!-- cache_translation_check_ko_5c178ce75f75b8bd0451f320ee3b1d4ddffab47ae6de19d37bb5d7b2c95ecaa1 -->
```
        <source>L&amp;ock unspent</source>
        <translation>L&amp;ock 미사용</translation>
    
ERR
The word "Lock" was not translated to Korean. It should be fully translated, and '&' shortcut should be preserved in the Korean translation.

Correct translation:
잠&금 미사용
```

<!-- cache_translation_check_ko_d0f3619cbfb0fb44863a284ab342a074c5d9355d416e26365701bf8095ea8efb -->
```
        <source>&amp;Unlock unspent</source>
        <translation>&amp; 사용 안 함 잠금 해제</translation>
    
ERR
The translation is awkward and unclear in Korean. "&Unlock unspent" refers to unlocking coins that are currently locked/unspent. The correct translation should fluently deliver this concept, such as:

Correct translation:
미사용 항목 &amp;잠금 해제

This keeps the "&" shortcut, eliminates spacing issues, and improves clarity.
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

<!-- cache_translation_check_ko_a8f383b1ca921e76eab449e8022820ec1c3747d6211d3b201edcc036e7ecd38d -->
```
        <source>Prune &amp;block storage to</source>
        <translation>블록 데이터를 지정된 크기로 축소합니다.(&amp;b) :</translation>
    
ERR
The translation does not accurately reflect the source. The source phrase "Prune &block storage to" is meant to be followed by a size, i.e., "Prune block storage to [X]". The Korean translation, "블록 데이터를 지정된 크기로 축소합니다.(&amp;b) :", turns the noun phrase into a full sentence and includes a colon, which is not in the original. The translation adds unnecessary explanation and wording. Also, the position of the shortcut (&amp;b) is changed, but that's allowable as long as it appears once.

Correct translation:
블록 저장소를 &amp;최대 크기로 축소

or, maintaining the original structure and recognizing "&block" is for the shortcut:
블록 저장소를 축소(&amp;b) 

But ideally, to preserve the intended meaning (assuming a value will follow):
블록 저장소를 &amp;다음 크기로 축소

If a value input follows, use:
블록 저장소를 &amp;다음 크기로 축소

If it's just as a standalone label:
블록 저장소 축소(&amp;b)

Choose based on interface context.
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

<!-- cache_translation_check_ko_b0320742a74665e9abde3b00cfce51e900f37e3052bc762395704bfaf5cb6760 -->
```
        <source>Enable R&amp;PC server</source>
        <extracomment>An Options window setting to enable the RPC server.</extracomment>
        <translation>R&amp;PC 서버를 가능하게 합니다.</translation>
    
ERR
The translation is understandable but sounds unnatural in Korean and doesn't use the most appropriate Korean IT terminology. "가능하게 합니다" is awkward; "활성화" is the more correct term for "enable" in this context. Also, the placement of "&" for the shortcut is acceptable.

Correct translation:
R&amp;PC 서버를 활성화합니다.
```

<!-- cache_translation_check_ko_3c2a3aa227ac90ae3527cae25fad8fdc4815dddd847e8285677358754e265c54 -->
```
        <source>W&amp;allet</source>
        <translation>지갑(&amp;A)</translation>
    
ERR
The ampersand (&amp;) is not in the correct position. In Korean Windows UI translation conventions, the ampersand should appear before the character that acts as the shortcut key. Also, 'A' is not a relevant shortcut in Korean for '지갑' (wallet); a typical choice would be 지(&amp;W)갑 or only &amp;지갑 if no shortcut is specified.

Correct translation:
지갑(&amp;W)
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

<!-- cache_translation_check_ko_03e78b5429d7eabad3ad5ec0b92bf59a9f165fb158e0f028bf2655661811f96a -->
```
        <source>Subtract &amp;fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>초기 설정값으로 수수료를 뺍니다.</translation>
    
ERR
The translation does not include the '&' indicating the shortcut key, and it omits specifying 'from amount' which is significant for clarity. Also, the translation reads as a general statement rather than an option label tied to amounts. It's important to relate "from amount" in the translation, and retain the '&' for shortcuts.

Correct translation:
기본적으로 금액에서 &수수료를 차감합니다.

Or, if matching the English structure for an option checkbox:
기본적으로 금액에서 &수수료를 차감

(The position of & can be adjusted for shortcut consistency in the UI context.)
```

<!-- cache_translation_check_ko_8da7b122c5682792ee601b5d3ad13222655026ff0a6f865f787aca7d660cf863 -->
```
        <source>&amp;Spend unconfirmed change</source>
        <translation>검증되지 않은 잔돈 쓰기 (&amp;S)</translation>
    
ERR
The translation introduces an unnecessary shortcut key (&amp;S) that does not correspond to the original English, where &amp; is only intended to appear next to "Spend". The current translation also places the shortcut at the end, which is non-standard for most Korean translations (the shortcut should be near the start if used at all and should match the English intent). Additionally, "검증되지 않은" is slightly less common than "확인되지 않은" for "unconfirmed" in the Bitcoin context.

Correct translation:
확인되지 않은 잔돈 사용(&amp;S)
or, if matching the English shortcut position:
&amp;확인되지 않은 잔돈 사용

But since the English puts the &amp; on "Spend", the best translation is:
&amp;확인되지 않은 잔돈 사용
```

<!-- cache_translation_check_ko_0f7a08645317ca13d8c231cf7318dc726677ff11ffee1dfcc54f48c81fe49b4f -->
```
        <source>Enable &amp;PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>PSBT 컨트롤을 가능하게 합니다.</translation>
    
ERR
The translation does not include the ampersand (&) used for keyboard shortcuts, which should appear exactly once, as in the source. The translation also does not match the succinctness of a label in an options window and reads more like a descriptive sentence.

Correct translation:
&PSBT 컨트롤 사용
```

<!-- cache_translation_check_ko_6bf9b8e04610974c8159372ddb2329ab6d174779f9af44d2b0def89998bfe827 -->
```
        <source>&amp;External signer script path</source>
        <translation>외부 서명자 스크립트 경로
 </translation>
    
ERR
There is an unwanted whitespace/line break at the end of the translation, which should be removed. The ampersand (&) indicating a shortcut key in the source is missing and should be included exactly once in the translation.

Correct translation:
&외부 서명자 스크립트 경로
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

<!-- cache_translation_check_ko_4f665bd91cae3cac4ec434c6be4a2885ade080fa62bfef59f77c0efaf2860e5e -->
```
        <source>M&amp;inimize on close</source>
        <translation>닫을때 최소화(&amp;I)</translation>
    
ERR
The Korean translation is understandable but contains spacing and formality issues. "닫을때" should be "닫을 때" (proper spacing), and "&amp;I" may not be the intended shortcut in Korean, though it is allowed to place it anywhere exactly once. For clarity and standard UI naming, translating "Minimize on close" as "닫을 때 최소화(&amp;I)" is acceptable.

Correct translation:
닫을 때 최소화(&amp;I)
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

<!-- cache_translation_check_ko_410f7f36af11e509b0ebae57b0fd51f55f2c231b755486ebe09270d313fa9311 -->
```
        <source>&amp;Third-party transaction URLs</source>
        <translation>제3자 트랜잭션 URL</translation>
    
ERR
The '&' character indicating a shortcut key in the source is missing from the translation, which should appear exactly once somewhere in the translation.

Correct translation:
&제3자 트랜잭션 URL
```

<!-- cache_translation_check_ko_88727734e3c03978f54419a5b38f21920f1ea3ac7ea8f971e877b26909bc031b -->
```
        <source>Use separate SOCKS&amp;5 proxy to reach peers via Tor onion services:</source>
        <translation>Tor onion 서비스를 통해 피어에 도달하려면 별도의 SOCKS &amp; 5 프록시를 사용하십시오.</translation>
    
ERR
The translation includes a spacing issue with "SOCKS &amp; 5"—there should be no space between "SOCKS" and "5", matching the source's "SOCKS&amp;5". Also, the ampersand for the shortcut key is placed incorrectly—it should be embedded within the translation at a logical place, appearing exactly once. The phrase "SOCKS5 프록시" is the standard term in Korean, and the shortcut key should be preserved.

Correct translation:
Tor onion 서비스를 통해 피어에 연결하려면 별도의 SOCKS&amp;5 프록시를 사용하십시오.
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

<!-- cache_translation_check_ko_82bb15665c7799a85efadbd4efdf602020b687e2bbf8170dc556fb133cfec00a -->
```
        <source>Age</source>
        <extracomment>Title of Peers Table column which indicates the duration (length of time) since the peer connection started.</extracomment>
        <translation>나이</translation>
    
ERR
The Korean word "나이" normally refers to a person's age (years old) and is misleading in this technical UI context (it should indicate how long a peer connection has been active). No format specifiers or spacing issues.

Suggested translations (more appropriate for connection duration):
- "연결 시간" 
- "연결된 시간" 
- "연결 지속 시간" 
- "접속 시간(경과)"

Pick one based on UI tone; e.g. "연결 시간" is concise and commonly used.
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

<!-- cache_translation_check_ko_b03ab3f8108d0e60bbee904c1660729defcc0066afb66198bbd7a3954b14086b -->
```
        <source>&amp;Copy address</source>
        <extracomment>Context menu action to copy the address of a peer.</extracomment>
        <translation>&amp; 주소 복사</translation>
    
ERR
There is an unnecessary space between '&' and '주소 복사', which creates an unwanted whitespace format issue. The ampersand (&) should directly precede the shortcut letter without a space for proper shortcut functionality.

Correct translation:
&주소 복사
```

<!-- cache_translation_check_ko_2500aba292b7a3344cbf971231bd34ee8bf47420b119b87713f8f19fafe30cfb -->
```
        <source>1 d&amp;ay</source>
        <translation>1일(&amp;a)</translation>
    
ERR
The Korean translation attempted to replicate the shortcut key by placing "&a" in parentheses, but this is not the standard way shortcuts are displayed in Korean UIs. Moreover, the original English uses "&" to indicate an access key (shortcut) for "a" in "day", but this should correspond to a proper location in the Korean label.

Correct translation:
1일(&amp;A) 

Or, if the shortcut is not meaningful in Korean, keep as:
1일(&amp;A)

But "&amp;a" should be uppercase to match the standard convention in Korean software, and there should be no extraneous spacing.
```

<!-- cache_translation_check_ko_ec8cfda155766c738a849dd4bce934ff9530bd1402680edf549c7922f9669cf3 -->
```
        <source>&amp;Copy IP/Netmask</source>
        <extracomment>Context menu action to copy the IP/Netmask of a banned peer. IP/Netmask is the combination of a peer's IP address and its Netmask. For IP address, see: https://en.wikipedia.org/wiki/IP_address.</extracomment>
        <translation>IP/Netmask 복사하기</translation>
    
ERR
The translation omits the '&' which is used for shortcut key assignment in menus. It must appear exactly once in the translation. Also, "복사하기" ("to copy") is less commonly used in menus than just "복사" ("Copy"), which better matches English command style.

Correct translation:
&IP/Netmask 복사

Or if consistency with Korean UI style is prioritized:
IP/Netmask(&C) 복사

But strictest to the prompt:

&IP/Netmask 복사
```

<!-- cache_translation_check_ko_5a4ba9676d667edc9e3b187ef6c9aaa2aadab5a13e82e772f5480a9cc0375f97 -->
```
        <source>Copy &amp;label</source>
        <translation>복사 &amp; 라벨</translation>
    
ERR
There is an unnecessary space between '&amp;' and '라벨' in the Korean translation. Shortcut keys should not have a space after '&'. Also, the word order is unnatural in Korean—it should be '라벨(&amp;L) 복사' or '라벨 복사(&amp;L)' if the shortcut is L, or at least '&amp;라벨 복사' if the '&' must be placed at the start.

Correct translation:
라벨(&amp;L) 복사
or
라벨 복사(&amp;L)
```

<!-- cache_translation_check_ko_53df314d2b734d1a76840df613f992b300aec1071ff978ee65a3cb2ae0be4d37 -->
```
        <source>Copy &amp;message</source>
        <translation>메세지 복사(&amp;m)</translation>
    
ERR
There is a spelling error in the Korean word "메세지", which should be "메시지". Also, the shortcut key is "&m", which should be preserved but can be mapped to either the Korean or the English letter. Usually, the shortcut is matched to the corresponding Korean consonant, but using "&m" as is, is acceptable if consistent across the UI. Additionally, spacing is correct.

Correct translation:
메시지 복사(&amp;m)
```

<!-- cache_translation_check_ko_89bd2f8f56e8e2bc841f5999c311ab74b07e2ba7aac385043317dc4c2b862e7a -->
```
        <source>Copy &amp;amount</source>
        <translation>복사 &amp; 금액</translation>
    
ERR
There is an unnecessary space between "복사" and "금액," which is not natural in Korean. The shortcut key (&) is preserved correctly, but the spacing should be fixed.

Correct translation:
복사(&amp;A) 금액

However, if aligning with the source order, "금액 복사(&amp;A)" would be most natural, but the shortcut key should match the original if possible. If the ampersand is to stay with "amount," then:

금액(&amp;A) 복사

Choose one that matches the actual software context, but remove the extra space.
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

<!-- cache_translation_check_ko_e6e8d571aa140592437bb8858e29ca2acc026edbe4f31a359bf3b8a589d5b207 -->
```
        <source>&amp;Verify</source>
        <translation>&amp;승인</translation>
    
ERR
The English "&Verify" means "확인" or "검증" in Korean, not "승인" (which means "approve" or "authorization"). The translation mistranslates the function.

Correct translation:
&확인
or
&검증
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

<!-- cache_translation_check_ko_5a4ba9676d667edc9e3b187ef6c9aaa2aadab5a13e82e772f5480a9cc0375f97 -->
```
        <source>Copy &amp;label</source>
        <translation>복사 &amp; 라벨</translation>
    
ERR
There is an unnecessary space between '&amp;' and '라벨' in the Korean translation. Shortcut keys should not have a space after '&'. Also, the word order is unnatural in Korean—it should be '라벨(&amp;L) 복사' or '라벨 복사(&amp;L)' if the shortcut is L, or at least '&amp;라벨 복사' if the '&' must be placed at the start.

Correct translation:
라벨(&amp;L) 복사
or
라벨 복사(&amp;L)
```

<!-- cache_translation_check_ko_89bd2f8f56e8e2bc841f5999c311ab74b07e2ba7aac385043317dc4c2b862e7a -->
```
        <source>Copy &amp;amount</source>
        <translation>복사 &amp; 금액</translation>
    
ERR
There is an unnecessary space between "복사" and "금액," which is not natural in Korean. The shortcut key (&) is preserved correctly, but the spacing should be fixed.

Correct translation:
복사(&amp;A) 금액

However, if aligning with the source order, "금액 복사(&amp;A)" would be most natural, but the shortcut key should match the original if possible. If the ampersand is to stay with "amount," then:

금액(&amp;A) 복사

Choose one that matches the actual software context, but remove the extra space.
```

<!-- cache_translation_check_ko_d684e72d7aa6f111bd64c9e5fa9b9127d14ddc08e834502bfc5702b693271fac -->
```
        <source>Copy transaction &amp;ID</source>
        <translation>복사 트랜잭션 &amp; 아이디</translation>
    
ERR
The translation is awkward and incorrectly orders the words. In Korean, the correct phrasing should be "트랜잭션 &ID 복사" or "&ID 트랜잭션 복사", but ideally "트랜잭션 &ID 복사" keeps the format closer to English with correct word ordering. The current translation "복사 트랜잭션 & 아이디" is unnatural and splits the phrase incorrectly.

Correct translation:
트랜잭션 &ID 복사
```

<!-- cache_translation_check_ko_dcd21ac0792b1fff73ab02c92f0577f08a7efbab6b6d625d0cc4c93faf715298 -->
```
        <source>Copy &amp;raw transaction</source>
        <translation>처리되지 않은 트랜잭션 복사</translation>
    
ERR
The ampersand (&) indicating the shortcut key is missing in the Korean translation. It should appear exactly once, as in the source, to designate the shortcut.

Correct translation:
&처리되지 않은 트랜잭션 복사

Or (as placement is flexible):
처리되지 않은 &트랜잭션 복사

But ensure there is exactly one '&' present.
```

<!-- cache_translation_check_ko_62f9c22497b4b8e36a7aeb8f77b6f90330a67e7e83531f97761b47f8b9824576 -->
```
        <source>Copy full transaction &amp;details</source>
        <translation>트랜잭션 전체와 상세내역 복사</translation>
    
ERR
The Korean translation omits the '&' shortcut key marker, which should appear exactly once, and the meaning should more closely match "Copy full transaction &details" (the '&' indicating where the shortcut is). Also, "트랜잭션 전체와 상세내역 복사" is a bit awkward; a better version would be more concise and natural.

Correct translation:
전체 거래 &세부정보 복사

This ensures the '&' is present, placement is natural, and the meaning closely matches the source.
```

<!-- cache_translation_check_ko_2f6e48caab7313cbb6bf5b6d4918e91390bc5a0f194cd6c482e57b69888865ea -->
```
        <source>&amp;Show transaction details</source>
        <translation>트랜잭션 상세내역 보여주기</translation>
    
ERR
The translation does not include the shortcut key indicator '&' as present in the source. The '&' should appear exactly once in the translation.

Correct translation:
&트랜잭션 상세내역 보여주기
```

<!-- cache_translation_check_ko_afd72dc8e5fc91a5270fed90a746b2ba5e1d3e424f623c1cf4c040abdba48cb6 -->
```
        <source>Increase transaction &amp;fee</source>
        <translation>트랜잭션 수수료 올리기</translation>
    
ERR
The '&' indicating the shortcut key is missing from the Korean translation. It should be present exactly once in the translation.

Correct translation:
트랜잭션 &수수료 올리기
```

<!-- cache_translation_check_ko_9af61ca789c74c7dc3db32d3c5134d53acc4ea6e8604a6cdc3f16c93e85ceea1 -->
```
        <source>A&amp;bandon transaction</source>
        <translation>트랜잭션 폐기하기</translation>
    
ERR
The translation does not preserve the '&' which indicates the shortcut key. The translation should include a single '&' at an appropriate place in the Korean text.

Correct translation:
트랜잭션 폐&기하기
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

<!-- cache_translation_check_ko_80415c91bd2b2ff78194af5ea6eb844484d2cd6d95890101872861dca3b09c08 -->
```
        <source>Error loading databases</source>
        <translation>데이터 베이스 불러오는데 오류</translation>
    
ERR
The Korean is colloquial and has spacing/grammar issues ("데이터 베이스" spacing and "불러오는데" is ungrammatical here). No format specifiers to preserve.

Suggested correct translations:
- 데이터베이스를 불러오는 중 오류가 발생했습니다.
- 데이터베이스 로드 오류
- 데이터베이스를 불러오는 중에 오류가 발생했습니다.
```

<!-- cache_translation_check_ko_9ffdbee1ae4ca96787e4ba40737e98ec3a961e661dd320007bfce1c0cd439210 -->
```
        <source>Error opening coins database</source>
        <translation>코인 데이터 베이스 열기 오류</translation>
    
ERR
Minor spacing and naturalness issue: "데이터베이스" is usually written without a space, and a more natural phrasing in Korean would include a subject/verb form.

Correct translation:
코인 데이터베이스 열기 오류가 발생했습니다.
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

<!-- cache_translation_check_ko_8b9678a8ed1ac1431dcac6a54ee294dc43a25c6ad87f16b76718599d7e26462d -->
```
        <source>Unable to find UTXO for external input</source>
        <translation> 외부 입력에 대한 UTXO를 찾을 수 없습니다</translation>
    
ERR
The translation is correct in meaning but has a leading stray space before the first character. Also you may prefer a slightly more natural alternative.

Corrected translation (remove leading space):
외부 입력에 대한 UTXO를 찾을 수 없습니다

Alternative natural phrasing:
외부 입력의 UTXO를 찾을 수 없습니다.
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

Number of issues: 73.
