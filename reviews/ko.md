# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ko</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bko%5D%20low%20quality)


```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>지갑 암호화 해제를 위해 입력된 비밀문구가 정확하지 않습니다. 비밀문구가 공백 문자 (0 바이트)를 포함하고 있습니다. 만약 비밀문구가 25.0 버전 이전의 비트코인 코어 소프트웨어에 의해 설정되었다면, 비밀문구를 첫 공백 문자 이전까지 입력해보세요. 이렇게 해서 성공적으로 입력되었다면, 차후 이런 문제가 발생하지 않도록 비밀문구를 새로이 설정해 주세요.</translation>
    
YES
The translation incorrectly uses "공백 문자" which means "whitespace character," instead of "null character" which should be translated as "널 문자" or "널 문자(즉, 0 바이트)." The original English text clearly distinguishes that the passphrase contains a null character, not simply a whitespace character. The dash "— but not including —" is translated as "이전까지" without emphasizing exclusion, which may cause slight ambiguity; better to clarify the exclusion.

Correct translation:
지갑 복호화를 위해 입력한 암호 문구가 올바르지 않습니다. 암호 문구에 널 문자(즉, 0 바이트)가 포함되어 있습니다. 만약 이 암호 문구가 25.0 버전 이전의 소프트웨어로 설정되었다면, 첫 번째 널 문자 직전까지의 문자만 사용하여 다시 시도해 보시기 바랍니다. 이렇게 성공하면, 앞으로 이 문제가 발생하지 않도록 새 암호 문구를 설정해 주세요.
```

```
        <source>About %1</source>
        <translation>%1 정보(A)</translation>
    
YES
The translation "%1 정보(A)" is problematic because the "(A)" is not a natural part of Korean translation for "About %1" and appears to be an unnecessary annotation or placeholder.

Correct translation:
%1 정보
```

```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>지불 요청하기 (QR 코드와 bitcoin을 생성합니다: URIs)</translation>
    
YES
The translation incorrectly places "bitcoin을 생성합니다" directly after "QR 코드와," which disrupts the meaning. The original phrase indicates that QR codes and bitcoin URIs are generated, not that "bitcoin" itself is generated. Also, "bitcoin:" in this context represents a URI scheme and should be kept as "bitcoin:" rather than translated or separated.

Correct translation:
지불 요청하기 (QR 코드와 bitcoin: URI를 생성합니다)
```

```
        <source>Ctrl+Q</source>
        <translation>Crtl + Q</translation>
    
YES
There is a typo in the translation: "Crtl" should be "Ctrl". Also, there should be no spaces around the plus sign to match the source format.

Correct translation:
Ctrl+Q
```

```
        <source>Load PSBT from clipboard…</source>
        <translation>PSBT 혹은 클립보드에서 불러오기</translation>
    
YES  
The translation "PSBT 혹은 클립보드에서 불러오기" means "Load PSBT or from clipboard," which changes the original meaning. The source instructs to load a PSBT from the clipboard specifically, not from either PSBT or clipboard separately. Also, the ellipsis (…) is omitted and should be preserved to indicate continuation.

Correct translation:  
"클립보드에서 PSBT 불러오기…"
```

```
        <source>No wallets available</source>
        <translation>사용 가능한 블록이 없습니다.</translation>
    
YES
The translation incorrectly refers to "블록" (block) instead of "지갑" (wallet). The source mentions wallets, so the correct translation should mention wallets, not blocks.

Correct translation:
사용 가능한 지갑이 없습니다.
```

```
        <source>Copy label</source>
        <translation>복사  라벨</translation>
    
YES  
There is an extra space between "복사" and "라벨". It should be a single space or no space depending on natural usage, but in this context, a single space is correct to separate the two words clearly.

Correct translation:  
복사 라벨
```

```
        <source>Copy amount</source>
        <translation>복사  금액</translation>
    
YES
There is an unnecessary space between "복사" and "금액". In Korean, "복사금액" or "금액 복사" would be more natural depending on the intended meaning (likely "금액 복사" meaning "Copy amount"). 

Correct translation:
금액 복사
```

```
        <source>Copy transaction ID and output index</source>
        <translation>거래  결과 인덱스값 혹은 ID 복사</translation>
    
YES  
The translation is problematic. It translates to "Copy transaction result index value or ID," which is not an accurate or natural rendering of "Copy transaction ID and output index." The word "결과" (result) is unnecessary and changes the meaning. Also, the phrase is ambiguous and awkward in Korean.

Correct translation:  
거래 ID 및 출력 인덱스 복사
```

```
        <source>Unlock unspent</source>
        <translation> 사용 안 함 잠금 해제</translation>
    
YES  
There is a leading whitespace in the translation that should be removed. The phrase "Unlock unspent" in the context of Bitcoin likely means "lock 해제" for unspent outputs, so a more accurate and clean translation without whitespace would be:

잠금 해제 사용 안 함
```

```
        <source>change from %1 (%2)</source>
        <translation>%1 로부터 변경 (%2)</translation>
    
YES  
The translation "%1 로부터 변경 (%2)" incorrectly uses "변경," which means "modification" or "change" as a verb or noun unrelated to Bitcoin "change" (잔돈 or 거스름돈). In the Bitcoin context, "change" refers to the leftover amount returned to the sender, so "잔돈" or "거스름돈" is appropriate. Also, the phrase "from %1 (%2)" should be represented naturally in Korean without awkward particles. A more accurate and natural translation would be:

"%1의 잔돈 (%2)"  
or  
"%1에서 발생한 잔돈 (%2)"

Recommended translation:  
%1의 잔돈 (%2)
```

```
        <source>Migrating the wallet will convert this wallet to one or more descriptor wallets. A new wallet backup will need to be made.
If this wallet contains any watchonly scripts, a new wallet will be created which contains those watchonly scripts.
If this wallet contains any solvable but not watched scripts, a different and new wallet will be created which contains those scripts.

The migration process will create a backup of the wallet before migrating. This backup file will be named &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak and can be found in the directory for this wallet. In the event of an incorrect migration, the backup can be restored with the "Restore Wallet" functionality.</source>
        <translation>지갑을 마이그레이션하면 이 지갑은 하나 이상의 설명자 지갑으로 변환됩니다. 새로운 지갑 백업이 필요합니다. 이 지갑에 watchonly 스크립트가 포함되어 있으면, 해당 watchonly 스크립트를 포함하는 새로운 지갑이 생성됩니다. 해결 가능하지만 관찰되지 않은 스크립트가 포함되어 있으면, 해당 스크립트를 포함하는 다른 새로운 지갑이 생성됩니다.

마이그레이션 과정은 마이그레이션 전에 지갑 백업을 생성합니다. 이 백업 파일은 -.legacy.bak로 명명되며 이 지갑의 디렉토리에서 찾을 수 있습니다. 마이그레이션이 잘못될 경우, '지갑 복원' 기능을 통해 백업을 복원할 수 있습니다.</translation>
    
YES
The translation is mostly accurate but has two key issues:
1. The backup file name in Korean translation is missing the wallet name and timestamp placeholders ("%1" or similar) from the source, instead showing just "-.legacy.bak".
2. There is inconsistent spacing and awkward phrasing in some parts, especially "watchonly" and "해결 가능하지만 관찰되지 않은 스크립트" could be more natural.

Corrected translation:

지갑을 마이그레이션하면 이 지갑은 하나 이상의 설명자 지갑(descriptor wallets)으로 변환됩니다. 새로운 지갑 백업을 만들어야 합니다. 이 지갑에 watchonly 스크립트가 포함된 경우, 해당 watchonly 스크립트를 포함하는 새로운 지갑이 생성됩니다. 해결 가능하나 관찰되지 않은(solvable but not watched) 스크립트가 포함된 경우, 해당 스크립트를 포함하는 다른 새로운 지갑이 생성됩니다.

마이그레이션 과정은 마이그레이션 전에 지갑 백업을 생성합니다. 이 백업 파일은 &lt;지갑 이름&gt;-&lt;타임스탬프&gt;.legacy.bak로 명명되며 이 지갑의 디렉토리에서 찾을 수 있습니다. 마이그레이션이 잘못될 경우, "지갑 복원" 기능을 통해 백업을 복원할 수 있습니다.
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>외부 서명 지원 없이 컴파일됨 (외부 서명에 필요) 개발자 참고 사항 [from:developer] "외부 서명"은 하드웨어 지갑과 같은 장치를 사용하는 것을 의미합니다.</translation>
    
YES
The translation includes extra and unnecessary content ("개발자 참고 사항 [from:developer] "외부 서명"은 하드웨어 지갑과 같은 장치를 사용하는 것을 의미합니다.") which is not present in the source and breaks the natural structure of the string. The explanation about "External signing" should not be included directly in the translation line but handled separately, such as in a comment or tooltip.

Correct translation:
외부 서명 지원 없이 컴파일됨 (외부 서명에 필요)
```

```
        <source>The label associated with this address list entry</source>
        <translation>현재 선택된 주소 필드의 라벨입니다.</translation>
    
YES  
The translation "현재 선택된 주소 필드의 라벨입니다." means "This is the label of the currently selected address field," which does not accurately convey the source meaning. The source sentence is describing "The label associated with this address list entry," referring to an entry in an address list, not the currently selected address or field.

A more accurate translation would be:  
"이 주소 목록 항목에 연결된 라벨"
```

```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>본 주소록 입력은 주소와 연계되었습니다.  이것은 보내는 주소들을 위해서만 변경될수 있습니다.</translation>
    
YES  
The translation is somewhat awkward and slightly inaccurate in tone and formality. The first sentence "본 주소록 입력은 주소와 연계되었습니다." literally means "This address book entry is linked with an address," which feels unnatural and unclear. The original English states "The address associated with this address list entry", so it should focus on "주소록 항목에 연결된 주소" or "이 주소록 항목과 연관된 주소."  

Also, the spacing after periods is inconsistent (extra spaces).  

Correct translation:  
"이 주소록 항목과 연관된 주소입니다. 이 주소는 보내기 주소에 대해서만 수정할 수 있습니다."
```

```
        <source>%1 is currently syncing.  It will download headers and blocks from peers and validate them until reaching the tip of the block chain.</source>
        <translation>%1가 현재 동기화 중입니다. 이것은 피어에서 헤더와 블록을 다운로드하고 블록 체인의 끝에 도달 할 때까지 유효성을 검사합니다.</translation>
    
YES
There is a spacing issue before "할" in the translation. In Korean, verb endings should not have a space before them when attached to preceding nouns or verbs. Also, "이것은" (this) is unnecessary and less natural in this context; it is better to directly refer to "%1" as the subject.

Correct translation:
%1가 현재 동기화 중입니다. 피어에서 헤더와 블록을 다운로드하고 블록 체인의 끝에 도달할 때까지 유효성을 검사합니다.
```

```
        <source>Number of script verification threads</source>
        <translation>스크립트 인증 쓰레드의 개수(V)</translation>
    
YES
The translation includes an unnecessary and unexplained "(V)" at the end, which is not present in the source text and may confuse readers. Additionally, "인증" (meaning "authentication" or "verification") is understandable but "검증" is the more common and precise term for "verification" in technical contexts. The phrase "쓰레드의 개수" is acceptable but could be more naturally phrased as "쓰레드 수."

Correct translation:
스크립트 검증 쓰레드 수
```

```
        <source>Set the number of script verification threads. Negative values correspond to the number of cores you want to leave free to the system.</source>
        <extracomment>Tooltip text for Options window setting that sets the number of script verification threads. Explains that negative values mean to leave these many cores free to the system.</extracomment>
        <translation>스크립트 검증 수명의 숫자를 설정하세요. 음수는 시스템에 묶이지 않는 자유로운 코어의 수를 뜻합니다.</translation>
    
YES  
The phrase "스크립트 검증 수명의 숫자" is awkward and incorrect. "수명" means "lifespan," which is irrelevant here. The correct term should be "스크립트 검증 스레드 수" (number of script verification threads). Additionally, the explanation of negative values is less clear than the source. A better translation is:

스크립트 검증 스레드 수를 설정하세요. 음수 값은 시스템에 남겨 둘 코어 수를 의미합니다.
```

```
        <source>Whether to set subtract fee from amount as default or not.</source>
        <extracomment>Tooltip text for Options window setting that sets subtracting the fee from a sending amount as default.</extracomment>
        <translation>수수료 감면을 초기값으로 할지 혹은 설정하지 않을지를 결정합니다.</translation>
    
YES
The translation misinterprets "subtract fee from amount." The original means to decide whether to subtract the transaction fee from the sending amount by default, not to "reduce" or "waive" the fee. The Korean "수수료 감면" means "fee reduction" or "fee waiver," which is incorrect here.

Correct translation:
"수수료를 금액에서 차감할지를 기본값으로 설정할지 여부입니다."
```

```
        <source>Spend unconfirmed change</source>
        <translation>검증되지 않은 잔돈 쓰기 (S)</translation>
    
YES  
The translation includes an unnecessary and unexplained "(S)" at the end, which is not present in the source and could cause confusion. It should be removed for accuracy and clarity.

Correct translation:  
검증되지 않은 잔돈 쓰기
```

```
        <source>External signer script path</source>
        <translation>외부 서명자 스크립트 경로
 </translation>
    
YES  
There is an unnecessary trailing whitespace (a non-breaking space) at the end of the translation which should be removed. Also, the translation is accurate and matches the source meaning.

Correct translation:  
외부 서명자 스크립트 경로
```

```
        <source>Connect through SOCKS5 proxy (default proxy):</source>
        <translation>SOCKS5 프록시를 거쳐 연결합니다(C) (기본 프록시):</translation>
    
YES
The translation includes an extraneous "(C)" which does not appear in the source text and disrupts the meaning. The phrase should be concise and directly reflect the source without added characters.

Correct translation:
SOCKS5 프록시를 통해 연결합니다(기본 프록시):
```

```
        <source>Show the icon in the system tray.</source>
        <translation>시스템 트레이에 있는 아이콘 숨기기</translation>
    
YES  
The English source says "Show the icon in the system tray." which means to display the icon. However, the Korean translation "시스템 트레이에 있는 아이콘 숨기기" means "Hide the icon in the system tray," which is the opposite meaning.

Correct translation:  
시스템 트레이에 아이콘 표시하기
```

```
        <source>Third-party URLs (e.g. a block explorer) that appear in the transactions tab as context menu items. %s in the URL is replaced by transaction hash. Multiple URLs are separated by vertical bar |.</source>
        <translation>내용 메뉴 아이템으로 거래내역 탭이 보이는 제3자 URL (블록익스프로러). URL에 %s는 트랜잭션 해시값으로 대체됩니다. 복수의 URL은 수직항목으로부터 분리됩니다. </translation>
    
YES
The translation contains some unnatural phrasing and inaccuracies:
- "내용 메뉴 아이템으로 거래내역 탭이 보이는" is an incorrect and confusing word order. It should say that third-party URLs appear as context menu items in the transactions tab.
- "블록익스프로러" should be more commonly "블록 탐색기" for "block explorer."
- "복수의 URL은 수직항목으로부터 분리됩니다." incorrectly translates "separated by vertical bar |." The vertical bar is a symbol and should be explicitly mentioned ("세로 막대기 |" or "수직 막대기 |") instead of "수직항목."
- "트랜잭션 해시값" is acceptable, but "거래 해시" is slightly more common.

Correct translation:
제3자 URL (예: 블록 탐색기)는 거래 탭에 컨텍스트 메뉴 항목으로 표시됩니다. URL 내의 %s는 거래 해시로 대체됩니다. 여러 URL은 세로 막대기 | 로 구분됩니다.
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>외부 서명 지원 없이 컴파일됨 (외부 서명에 필요) 개발자 참고 사항 [from:developer] "외부 서명"은 하드웨어 지갑과 같은 장치를 사용하는 것을 의미합니다.</translation>
    
YES
The translation includes extra and unnecessary content ("개발자 참고 사항 [from:developer] "외부 서명"은 하드웨어 지갑과 같은 장치를 사용하는 것을 의미합니다.") which is not present in the source and breaks the natural structure of the string. The explanation about "External signing" should not be included directly in the translation line but handled separately, such as in a comment or tooltip.

Correct translation:
외부 서명 지원 없이 컴파일됨 (외부 서명에 필요)
```

```
        <source>The configuration file is used to specify advanced user options which override GUI settings. Additionally, any command-line options will override this configuration file.</source>
        <extracomment>Explanatory text about the priority order of instructions considered by client. The order from high to low being: command-line, configuration file, GUI settings.</extracomment>
        <translation>GUI 설정을 우선하는 고급 사용자 옵션을 지정하는 데 사용되는 설정파일 입니다. 추가로 모든 명령 줄 옵션도 이 설정 파일보다 우선시 됩니다.</translation>
    
YES  
The translation reverses the priority order of overriding: it says "GUI settings are prioritized" whereas the source states that advanced user options override GUI settings, and command-line options override the config file. The phrase "GUI 설정을 우선하는" incorrectly implies GUI settings have higher priority, which is opposite to the source.

Correct translation:  
"설정 파일은 GUI 설정을 무시하고 고급 사용자 옵션을 지정하는 데 사용됩니다. 또한, 모든 명령줄 옵션은 이 설정 파일을 무시합니다."
```

```
        <source>Whether we relay addresses to this peer.</source>
        <extracomment>Tooltip text for the Address Relay field in the peer details area, which displays whether we relay addresses to this peer (Yes/No).</extracomment>
        <translation>이 피어에게 지갑주소를 릴레이할지를 결정합니다.</translation>
    
YES  
The translation "이 피어에게 지갑주소를 릴레이할지를 결정합니다." translates to "Decides whether to relay wallet addresses to this peer." This is more of an explanatory description rather than a direct rendition of the source sentence "Whether we relay addresses to this peer." which sounds like a tooltip or label indicating the status or option itself, not a decision process. Also, "지갑주소" (wallet address) is a narrower meaning whereas the source simply says "addresses," which could also include P2P network addresses.  

A more accurate and neutral translation better suited as a tooltip would be:  
"이 피어에게 주소를 릴레이하는지 여부."  
(This literally means "Whether we relay addresses to this peer.")
```

```
        <source>Address Relay</source>
        <extracomment>Text title for the Address Relay field in the peer details area, which displays whether we relay addresses to this peer (Yes/No).</extracomment>
        <translation>지갑주소를 릴레이합니다.</translation>
    
YES
The original English "Address Relay" is a concise label/title indicating a feature or field about relaying addresses to a peer. The Korean translation "지갑주소를 릴레이합니다." means "We relay wallet addresses," which is a full sentence rather than a short label and it specifically says "wallet address" whereas "address" here can mean any Bitcoin network address, not only wallet addresses.

A more appropriate translation should be short and generic, matching the label style:

Correct translation:
주소 릴레이
```

```
        <source>Addresses Processed</source>
        <extracomment>Text title for the Addresses Processed field in the peer details area, which displays the total number of addresses received from this peer that were processed (excludes addresses that were dropped due to rate-limiting).</extracomment>
        <translation>처리된 지갑</translation>
    
YES
The English source "Addresses Processed" refers to the number of addresses processed, where "addresses" means network or wallet addresses. The Korean translation "처리된 지갑" means "processed wallets," which changes the meaning incorrectly from "addresses" to "wallets." The correct translation should preserve the meaning of "addresses," for example:

Correct translation:
처리된 주소
```

```
        <source>Addresses Rate-Limited</source>
        <extracomment>Text title for the Addresses Rate-Limited field in the peer details area, which displays the total number of addresses received from this peer that were dropped (not processed) due to rate-limiting.</extracomment>
        <translation>지갑의 Rate제한</translation>
    
YES
The translation "지갑의 Rate제한" is incorrect and partially untranslated—it mixes Korean and English without proper localization. The source refers to "Addresses Rate-Limited," meaning multiple addresses have been rate-limited (dropped due to rate-limiting), not just related to a wallet ("지갑").

A better translation would be:
"주소들 속도 제한됨"  
or more natural:
"주소 속도 제한"  
to reflect the plural "Addresses" and the concept of rate-limiting.
```

```
        <source>Elapsed time since a novel transaction accepted into our mempool was received from this peer.</source>
        <extracomment>Tooltip text for the Last Transaction field in the peer details area.</extracomment>
        <translation>이 피어에서 새 트랜잭션이 수신된 이후 경과된 시간입니다.</translation>
    
YES  
The translation shortens the original meaning and omits important details. The English source indicates the elapsed time is "since a novel transaction accepted into our mempool was received from this peer," which means the transaction must be both new (novel) and accepted into the mempool. The given Korean translation simply says "elapsed time since a new transaction was received from this peer," missing the "accepted into our mempool" aspect. For accuracy and completeness, it should be fully reflected.

Correct translation:  
"이 피어로부터 우리의 메모리 풀에 수락된 새 트랜잭션이 수신된 이후 경과된 시간입니다."
```

```
        <source>Inbound: initiated by peer</source>
        <extracomment>Explanatory text for an inbound peer connection.</extracomment>
        <translation>시작점 : 동기에 의해 시작됨</translation>
    
YES  
The translation is inaccurate and awkward. "Inbound: initiated by peer" refers to an incoming connection started by a peer. The given translation "시작점 : 동기에 의해 시작됨" literally means "Starting point: started by motivation," which is incorrect and unrelated to the context.

Correct translation:  
"수신: 피어에 의해 시작됨"
```

```
        <source>Outbound Manual: added using RPC %1 or %2/%3 configuration options</source>
        <extracomment>Explanatory text for an outbound peer connection that was established manually through one of several methods. The numbered arguments are stand-ins for the methods available to establish manual connections.</extracomment>
        <translation>아웃바운드 매뉴얼 : RPC %1 이나 %2/%3 을 사용해서 환경설정 옵션을 추가</translation>
    
YES  
The translation contains unnecessary spaces before and after colons and around particles, which is not natural in Korean. Also, the phrase "환경설정 옵션을 추가" directly means "added configuration options," but the source implies that outbound manual connections were added using the RPC or configuration options, not that the options themselves were added.

A more natural and accurate Korean translation would be:

아웃바운드 매뉴얼: RPC %1 또는 %2/%3 환경설정 옵션을 사용해 추가됨

This phrasing removes extra spaces, uses "또는" instead of "이나" for better flow, and uses "추가됨" to clearly indicate "added" for the outbound manual connection.
```

```
        <source>Outbound Address Fetch: short-lived, for soliciting addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to request addresses from a peer.</extracomment>
        <translation>아웃바운드 주소 가져오기: 단기, 주소 요청용
 </translation>
    
YES  
The translation has an extra trailing whitespace character at the end after "주소 요청용". Also, the translation could be improved for clarity by translating "short-lived" more naturally and specifying "for soliciting addresses" more clearly in Korean.

Correct translation:  
아웃바운드 주소 조회: 단기 접속, 주소 요청용
```

```
        <source>Copy label</source>
        <translation>복사  라벨</translation>
    
YES  
There is an extra space between "복사" and "라벨". It should be a single space or no space depending on natural usage, but in this context, a single space is correct to separate the two words clearly.

Correct translation:  
복사 라벨
```

```
        <source>Copy amount</source>
        <translation>복사  금액</translation>
    
YES
There is an unnecessary space between "복사" and "금액". In Korean, "복사금액" or "금액 복사" would be more natural depending on the intended meaning (likely "금액 복사" meaning "Copy amount"). 

Correct translation:
금액 복사
```

```
        <source>Request payment to …</source>
        <translation>에게 지불을 요청</translation>
    
YES
The translation "에게 지불을 요청" is incomplete and lacks the subject or object before the particle "에게," which indicates the recipient of the payment request. The English source "Request payment to …" implies that "to [someone]" or "to [an address]" should follow. The Korean translation should reflect that structure clearly.

Correct translation:
"…에게 지불을 요청" 

If the ellipsis (…) represents a placeholder (e.g., a name or address), it should be retained as in the source or replaced with a format specifier if applicable:

"…에게 지불을 요청" or "지불 요청하기: %s" depending on context.

If no placeholder is intended and the phrase is generic, a more natural translation would be:

"지불 요청하기" (Request payment)

But to keep the structure consistent with the source with an explicit "to …", the translation must include the subject before "에게".
```

```
        <source>Custom change address</source>
        <translation>주소 변경</translation>
    
YES
The source phrase "Custom change address" refers to a specific Bitcoin wallet address used for receiving change (the leftover funds from a transaction). The provided translation "주소 변경" means "change address" or "address change" in the sense of "changing an address" (verb), which is incorrect and ambiguous. It does not convey the meaning of a user-specified/custom Bitcoin change address.

A better translation would be:
"사용자 지정 잔돈 주소" or "사용자 정의 잔돈 주소"  
which explicitly means "Custom change address" in the context of Bitcoin transactions.
```

```
        <source>Using the fallbackfee can result in sending a transaction that will take several hours or days (or never) to confirm. Consider choosing your fee manually or wait until you have validated the complete chain.</source>
        <translation>고장 대체 수수료를 사용하게 될 경우 보낸 거래가 승인이 완료 될 때까지 몇 시간 혹은 몇 일 (혹은 영원히) 이 걸릴 수 있습니다. 수동으로 수수료를 선택하거나 전체 체인의 유효성이 검증될 때까지 기다리십시오.</translation>
    
YES  
The phrase "고장 대체 수수료" is not the correct translation for "fallbackfee." "고장" typically means "breakdown" or "malfunction," which is inappropriate in this context. The correct translation for "fallback fee" in Korean Bitcoin terminology would be "대체 수수료" or "대체 수수료(fallbackfee)" without "고장."  

Also, spacing issues: "승인이 완료 될 때까지" should be "승인이 완료될 때까지" (no space in '완료될').  

Correct translation:  
fallbackfee는 승인이 완료될 때까지 몇 시간 또는 며칠(또는 영원히) 걸릴 수 있는 거래를 보내는 결과를 초래할 수 있습니다. 수수료를 수동으로 선택하거나 전체 체인을 검증할 때까지 기다리십시오.  

Full corrected translation:  
<translation>대체 수수료(fallbackfee)를 사용하면 거래가 몇 시간 또는 며칠(또는 영원히) 확인되지 않을 수 있습니다. 수수료를 수동으로 선택하거나 전체 체인을 검증할 때까지 기다리십시오.</translation>
```

```
        <source>Create Unsigned</source>
        <translation>사인되지 않은 것을 생성(e)</translation>
    
YES
The translation contains unnecessary and unclear elements: "(e)" is not appropriate or meaningful in Korean here. The phrase "사인되지 않은 것을 생성" is somewhat understandable but not natural or concise. A more natural and idiomatic translation for "Create Unsigned" in the Bitcoin context (creating an unsigned transaction) would be:

"서명되지 않은 거래 생성" or simply "미서명 생성" depending on context.

Correct translation:
서명되지 않은 거래 생성
```

```
        <source>Not signalling Replace-By-Fee, BIP-125.</source>
        <translation>'수수료로-대체', BIP-125를 지원하지 않습니다.</translation>
    
YES  
The translation is problematic. The phrase "Not signalling Replace-By-Fee, BIP-125." means that the transaction does not signal support for Replace-By-Fee according to BIP-125. The translation "'수수료로-대체', BIP-125를 지원하지 않습니다." literally means "'Replace with fee', BIP-125 is not supported," which is slightly off and awkwardly phrased, and the use of single quotes around '수수료로-대체' is unnatural in Korean.

A better translation would be:  
"BIP-125인 Replace-By-Fee 신호를 보내지 않습니다."  
or  
"Replace-By-Fee(BIP-125)를 신호하지 않습니다."  

These better convey "not signalling" the Replace-By-Fee feature.

Correct translation:  
BIP-125인 Replace-By-Fee 신호를 보내지 않습니다.
```

```
        <source>Warning: Unknown change address</source>
        <translation>경고: 알려지지 않은 주소 변경입니다</translation>
    
YES  
The translation "경고: 알려지지 않은 주소 변경입니다" incorrectly translates "change address" as "주소 변경" which means "address change" rather than "change address" (i.e., a Bitcoin change address). The correct translation should treat "change address" as a compound noun referring to a specific type of address. A better translation would be:  

경고: 알 수 없는 체인지 주소  

or  

경고: 알 수 없는 변경 주소  

"체인지 주소" (transliteration of "change address") is commonly used in Korean Bitcoin terminology, or alternatively "변경 주소" can be used, but it should not be translated as "주소 변경" which implies "changing an address."  

Correct translation:  
경고: 알 수 없는 체인지 주소
```

```
        <source>Subtract fee from amount</source>
        <translation>송금액에서 수수료 공제(U)</translation>
    
YES  
The translation contains an unnecessary and unexplained "(U)" at the end, which is not present in the source and seems out of place. Also, "송금액" (remittance amount) is less appropriate than "금액" or "총액" for "amount" in the Bitcoin context.

A better translation would be:  
"금액에서 수수료 차감"  
or more explicitly:  
"금액에서 수수료를 차감"  

This correctly conveys "Subtract fee from amount" without extraneous characters.
```

```
        <source>Received with</source>
        <translation>받은 주소 :</translation>
    
YES  
The English source "Received with" is a phrase that typically precedes the method or address used to receive something (e.g., Bitcoin). The Korean translation "받은 주소 :" means "Received address:" which is more specific than the original and adds a colon unnecessarily. This could confuse the meaning because "Received with" does not necessarily mean "received address".

A more accurate translation of "Received with" would be simply "받음" or "받은" without specifying "주소" (address) or adding a colon.

Correct translation:  
받은 내용으로
```

```
        <source>Received from</source>
        <translation>보낸 주소 :</translation>
    
YES
The source text "Received from" indicates that something was received from a source, which suggests the translation should mean "받음 (from)" or "수신자", or more naturally "받은 주소" if referring to an address.

The provided translation "보낸 주소 :" means "Sent address :", which is the opposite of "Received from".

Correct translation:
받은 주소:
```

```
        <source>Received with</source>
        <translation>받은 주소 :</translation>
    
YES  
The English source "Received with" is a phrase that typically precedes the method or address used to receive something (e.g., Bitcoin). The Korean translation "받은 주소 :" means "Received address:" which is more specific than the original and adds a colon unnecessarily. This could confuse the meaning because "Received with" does not necessarily mean "received address".

A more accurate translation of "Received with" would be simply "받음" or "받은" without specifying "주소" (address) or adding a colon.

Correct translation:  
받은 내용으로
```

```
        <source>Copy label</source>
        <translation>복사  라벨</translation>
    
YES  
There is an extra space between "복사" and "라벨". It should be a single space or no space depending on natural usage, but in this context, a single space is correct to separate the two words clearly.

Correct translation:  
복사 라벨
```

```
        <source>Copy amount</source>
        <translation>복사  금액</translation>
    
YES
There is an unnecessary space between "복사" and "금액". In Korean, "복사금액" or "금액 복사" would be more natural depending on the intended meaning (likely "금액 복사" meaning "Copy amount"). 

Correct translation:
금액 복사
```

```
        <source>Copy transaction ID</source>
        <translation>복사 트랜잭션  아이디</translation>
    
YES
The translation has extra spacing and the phrase is not natural Korean. "Copy transaction ID" should be translated as "거래 ID 복사" without extra spaces.  
Correct translation:  
거래 ID 복사
```

```
        <source>Copy raw transaction</source>
        <translation>처리되지 않은 트랜잭션 복사</translation>
    
YES  
The phrase "Copy raw transaction" should be translated more accurately in the context of Bitcoin. "처리되지 않은 트랜잭션" literally means "unprocessed transaction," which is not the same as "raw transaction." The correct term for "raw transaction" in Korean Bitcoin terminology is typically "원시 트랜잭션."  

Correct translation:  
원시 트랜잭션 복사
```

```
        <source>%s corrupt. Try using the wallet tool bitcoin-wallet to salvage or restoring a backup.</source>
        <translation>%s가 손상되었습니다. '비트 코인-지갑'을 사용하여 백업을 구제하거나 복원하십시오.</translation>
    
YES  
The translation incorrectly adds spaces within the loanword '비트코인' (Bitcoin) and translates 'wallet tool bitcoin-wallet' as '비트 코인-지갑', which is unnatural in Korean. Also, 'salvage or restoring a backup' is mismatched in structure; the source says 'to salvage or restoring' which is ungrammatical, but ideally the Korean should reflect the infinitive form for both actions.

Correct translation:  
%s가 손상되었습니다. 비트코인 지갑 도구 bitcoin-wallet을 사용하여 복구하거나 백업을 복원해 보십시오.
```

```
        <source>Cannot upgrade a non HD split wallet from version %i to version %i without upgrading to support pre-split keypool. Please use version %i or no version specified.</source>
        <translation>사전분리 키풀를 지원하기 위해서 업그레이드 하지 않고는 Non HD split 지갑의 %i버젼을 %i버젼으로 업그레이드 할 수 없습니다. %i버젼을 활용하거나 구체화되지 않은 버젼을 활용하세요.</translation>
    
YES
The translation has awkward phrasing and some grammatical issues in Korean. Specifically:
- "사전분리 키풀를" should be "사전 분리 키풀을" (spacing and subject particle).
- The phrase "Non HD split 지갑의 %i버젼을 %i버젼으로 업그레이드 할 수 없습니다" is unnatural and could be better structured.
- "구체화되지 않은 버젼" is a bit unclear; "버전이 지정되지 않은" or "버전이 명시되지 않은" sounds more natural.
- "버젼" should be standardized as "버전" (the correct loanword spelling in Korean).

A more natural and accurate translation would be:

"사전 분리 키풀을 지원하도록 업그레이드하지 않으면 Non-HD 스플릿 지갑을 버전 %i에서 버전 %i로 업그레이드할 수 없습니다. 버전 %i를 사용하거나 버전을 지정하지 마십시오."

This keeps the format specifiers intact and improves readability.
```

```
        <source>Invalid or corrupt peers.dat (%s). If you believe this is a bug, please report it to %s. As a workaround, you can move the file (%s) out of the way (rename, move, or delete) to have a new one created on the next start.</source>
        <translation>유효하지 않거나 손상된 peers.dat(%s). 만약 이게 버그인 경우에, %s이쪽으로 리포트해주세요.  새로 만들어서 시작하기 위한 해결방법으로 %s파일을 옮길 수 있습니다. (이름 재설정, 파일 옮기기 혹은 삭제).</translation>
    
YES  
The translation has spacing and formality issues that affect clarity and naturalness in Korean. It also misplaces some punctuation and omits particles needed for smooth reading. The suggested correction improves formality, spacing, and sentence flow:

Correct translation:  
유효하지 않거나 손상된 peers.dat(%s) 파일입니다. 만약 이것이 버그라고 생각되시면, %s로 신고해 주세요. 해결 방법으로는 다음 시작 시 새 파일이 생성되도록 %s 파일을 옮기거나(이름 변경, 이동 또는 삭제) 처리할 수 있습니다.
```

```
        <source>No wallet file format provided. To use createfromdump, -format=&lt;format&gt; must be provided.</source>
        <translation>shshhdchb bdfjj fb  rciivfjb doffbfbdjdj</translation>
    
YES
The translation consists of nonsensical characters and does not convey the meaning of the source text. It appears to be random typing rather than a proper Korean translation.

Correct translation:
지갑 파일 형식이 제공되지 않았습니다. createfromdump를 사용하려면 -format=&lt;format&gt; 옵션을 반드시 제공해야 합니다.
```

```
        <source>Cannot set -forcednsseed to true when setting -dnsseed to false.</source>
        <translation>naravfbj. dufb jdncnlfs. jx dhcji djc d jcbc jdnbfbicb </translation>
    
YES
The translation is completely nonsensical and does not convey the meaning of the source text. It appears to be random characters without any relation to the original sentence.

Correct translation:
"-dnsseed를 false로 설정할 때는 -forcednsseed를 true로 설정할 수 없습니다."
```

```
        <source>Dump file %s does not exist.</source>
        <translation>파일 버리기 %s 존재 안함</translation>
    
YES
The translation is inaccurate and unnatural. "Dump file" should be translated in a way that clearly conveys a "dump file" (덤프 파일), not literally "파일 버리기" which means "file dumping" or "throwing away a file." Also, the phrase "존재 안함" is informal and somewhat incomplete; a more natural phrasing is "존재하지 않습니다" or "존재하지 않음."

Correct translation:
덤프 파일 %s이(가) 존재하지 않습니다.
```

```
        <source>Error creating %s</source>
        <translation>만들기 오류 %s</translation>
    
YES
The Korean translation word order and particle usage are incorrect and unnatural. "%s 생성 오류" or "%s 생성 중 오류" would be more appropriate and grammatically correct.

Correct translation:
%s 생성 오류
```

```
        <source>Failed to verify database</source>
        <translation>데이터베이스를 검증 실패</translation>
    
YES  
The Korean translation is grammatically incorrect and unnatural. The phrase "데이터베이스를 검증 실패" is not a proper sentence because "검증" (verification) is a noun here, and "실패" (failure) cannot directly follow it without a proper verb form. The correct form should use a verb expression to indicate failure.

Correct translation:  
데이터베이스 검증에 실패했습니다
```

```
        <source>Invalid netmask specified in -whitelist: '%s'</source>
        <translation>유효하지 않은 넷마스크가 -whitelist: '%s" 를 통해 지정됨</translation>
    
YES
There is a mismatch in quotation marks around '%s': the source uses single quotes ('%s'), but the translation uses a single quote at the start and a double quote at the end ('%s"). Also, spacing around punctuation can be improved for natural Korean.

Correct translation:
유효하지 않은 넷마스크가 -whitelist: '%s' 에서 지정됨
```

```
        <source>SQLiteDatabase: Failed to prepare statement to verify database: %s</source>
        <translation>에스큐엘라이트 데이터베이스 : 데이터베이스를 확인하는 실행문 준비에 실패하였습니다 : %s.</translation>
    
YES  
There are spacing issues around the colon ":" and a redundant period at the end. In Korean, spaces before and after punctuation such as colons should be removed, and typically no period is needed if the source does not have one. Also, "SQLiteDatabase" should be transliterated or kept as is without spaces to maintain clarity.  

Correct translation:  
SQLiteDatabase: 데이터베이스를 확인하는 실행문 준비에 실패하였습니다: %s
```

```
        <source>SQLiteDatabase: Failed to read database verification error: %s</source>
        <translation>에스큐엘라이트 데이터베이스 : 데이터베이스 읽기를 실패하였습니다: %s</translation>
    
YES  
There is an unnecessary space before and after the colon in the translation. In Korean, spacing around punctuation like colons should not have spaces. Also, the original message sounds slightly unnatural; a more fluent Korean translation would be:

Correct translation:  
에스큐엘라이트데이터베이스: 데이터베이스 검증 오류를 읽지 못했습니다: %s
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>거래액은 반드시 0보다 큰 값이어야 합니다.</translation>
    
YES  
The original English says "Transaction amounts must not be negative," which means the amounts can be zero or positive. However, the Korean translation "거래액은 반드시 0보다 큰 값이어야 합니다." means "Transaction amounts must be greater than 0," excluding zero, which is inaccurate.

Correct translation:  
거래액은 음수가 아니어야 합니다.  
or  
거래액은 음수일 수 없습니다.
```

```
        <source>Unknown -blockfilterindex value %s.</source>
        <translation>알 수 없는 -blockfileterindex 값 %s.</translation>
    
YES
There is a typo in the translation: "-blockfileterindex" should be "-blockfilterindex" to match the source.

Correct translation:
알 수 없는 -blockfilterindex 값 %s.
```
</details>
