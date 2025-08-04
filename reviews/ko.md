# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ko</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bko%5D%20low%20quality)


```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>지갑 암호화 해제를 위해 입력된 비밀문구가 정확하지 않습니다. 비밀문구가 공백 문자 (0 바이트)를 포함하고 있습니다. 만약 비밀문구가 25.0 버전 이전의 비트코인 코어 소프트웨어에 의해 설정되었다면, 비밀문구를 첫 공백 문자 이전까지 입력해보세요. 이렇게 해서 성공적으로 입력되었다면, 차후 이런 문제가 발생하지 않도록 비밀문구를 새로이 설정해 주세요.</translation>
    
YES, the translation contains an error in the explanation of the "null character." The original English text specifies a "null character (ie - a zero byte)" which refers to a specific control character. The Korean translation incorrectly states it as "공백 문자 (0 바이트)" which translates to "whitespace character (0 byte)." While a null character does have a value of zero bytes, it is not the same as a general whitespace character. A more accurate translation would be "널 문자 (즉, 0 바이트)" or simply "0 바이트 문자".

Here's the corrected translation:

YES, the translation contains an error in explaining "null character". The Korean translation uses "공백 문자 (0 바이트)" (whitespace character (0 byte)) which is not entirely accurate as a null character is a specific control character, not general whitespace.

Correct translation:
지갑 암호화 해제를 위해 입력된 비밀문구가 정확하지 않습니다. 비밀문구가 널 문자 (즉, 0 바이트)를 포함하고 있습니다. 만약 비밀문구가 25.0 버전 이전의 이 소프트웨어 버전에 의해 설정되었다면, 첫 번째 널 문자 바로 앞까지의 문자만 사용하여 다시 시도해 보세요. 이것이 성공적이라면, 향후 이러한 문제를 피하기 위해 새 비밀문구를 설정해 주십시오.
```

```
        <source>About %1</source>
        <translation>%1 정보(A)</translation>
    
YES, The translation is problematic. The hanging 'A' at the end of the translation is unnecessary and unprofessional.
Correct translation: %1 정보
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>지갑 주소가 본인 소유인지 증명하기 위해 메시지를 서명합니다.</translation>
    
YES - The translation is grammatically incorrect and unnatural in Korean. It also misses the "Bitcoin" context.

Correct translation: 비트코인 주소가 본인 소유인지 증명하기 위해 메시지에 서명하세요.
```

```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>지불 요청하기 (QR 코드와 bitcoin을 생성합니다: URIs)</translation>
    
YES: The translation incorrectly states that it generates "bitcoin" instead of "bitcoin: URIs". The colon is important for the URI format.
Correct translation: 지불 요청하기 (QR 코드와 bitcoin: URIs 생성)
```

```
        <source>Ctrl+Q</source>
        <translation>Crtl + Q</translation>
    
YES, The translation has a typo in the letter 'l' and 'r' in 'Ctrl'. It should be "Ctrl + Q".
Ctrl + Q
```

```
        <source>Load PSBT from clipboard…</source>
        <translation>PSBT 혹은 클립보드에서 불러오기</translation>
    
YES, The translation is problematic because it incorrectly translates "Load PSBT from clipboard" as "PSBT or load from clipboard". The phrase "PSBT or" is not present in the original English text.

The correct translation should be:
PSBT를 클립보드에서 불러오기…
```

```
        <source>Open a bitcoin: URI</source>
        <translation>bitcoin 열기: URI</translation>
    
YES, The translation is incorrect. The word order and the particle placement are unnatural in Korean. The correct translation should be "bitcoin: URI 열기".
bitcoin: URI 열기
```

```
        <source>No wallets available</source>
        <translation>사용 가능한 블록이 없습니다.</translation>
    
YES, The translation is incorrect. The Korean translation "사용 가능한 블록이 없습니다." means "There are no available blocks." which is not related to the English source "No wallets available."

The correct translation for "No wallets available" in the context of Bitcoin would be "사용 가능한 지갑이 없습니다."

NO
```

```
        <source>Copy label</source>
        <translation>복사  라벨</translation>
    
YES, The spacing between "복사" and "라벨" is incorrect. The correct translation is "복사 라벨".
```

```
        <source>Copy amount</source>
        <translation>복사  금액</translation>
    
YES, The spacing between "복사" and "금액" is incorrect. It should be "복사 금액".
NO
```

```
        <source>Copy transaction ID and output index</source>
        <translation>거래  결과 인덱스값 혹은 ID 복사</translation>
    
YES, The translation is problematic. The English source text "Copy transaction ID and output index" is translated as "거래 결과 인덱스값 혹은 ID 복사" which means "Copy transaction result index or ID". The word "output" is translated as "결과" (result), which is not accurate in the context of Bitcoin transactions. The correct translation should include "output" as "출력" or "아웃풋" to accurately reflect the meaning of "output index".

The correct translation is:
"거래 ID 및 출력 인덱스 복사"
```

```
        <source>Unlock unspent</source>
        <translation> 사용 안 함 잠금 해제</translation>
    
YES, The translation is inaccurate and does not convey the intended meaning of "Unlock unspent" in the context of Bitcoin. "사용 안 함 잠금 해제" literally translates to "Unlock non-usage" or "Unlock disabled," which is not related to Bitcoin unspent transaction outputs (UTXOs).

The correct translation should convey the idea of unlocking or accessing unspent Bitcoin amounts. A more appropriate translation would be:

"미사용 자산 사용 가능" (Mi-yong ja-san sa-yong ga-neung) which means "Unspent assets usable" or "Unlock unspent funds."

Correct Translation: 미사용 자산 사용 가능
```

```
        <source>change from %1 (%2)</source>
        <translation>%1 로부터 변경 (%2)</translation>
    
YES, The translation is problematic because it misinterprets the meaning of "change" in the context of Bitcoin. In Bitcoin transactions, "change" refers to the unspent portion of the input that is returned to the sender, not a general change or modification. The Korean translation "%1 로부터 변경 (%2)" translates to "change from %1 (%2)" which conveys a sense of modification or alteration, not the specific Bitcoin concept of change.

A more accurate translation in this context would be:

%1 에서의 잔돈 (%2)
```

```
        <source>Migrating the wallet will convert this wallet to one or more descriptor wallets. A new wallet backup will need to be made.
If this wallet contains any watchonly scripts, a new wallet will be created which contains those watchonly scripts.
If this wallet contains any solvable but not watched scripts, a different and new wallet will be created which contains those scripts.

The migration process will create a backup of the wallet before migrating. This backup file will be named &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak and can be found in the directory for this wallet. In the event of an incorrect migration, the backup can be restored with the "Restore Wallet" functionality.</source>
        <translation>지갑을 마이그레이션하면 이 지갑은 하나 이상의 설명자 지갑으로 변환됩니다. 새로운 지갑 백업이 필요합니다. 이 지갑에 watchonly 스크립트가 포함되어 있으면, 해당 watchonly 스크립트를 포함하는 새로운 지갑이 생성됩니다. 해결 가능하지만 관찰되지 않은 스크립트가 포함되어 있으면, 해당 스크립트를 포함하는 다른 새로운 지갑이 생성됩니다.

마이그레이션 과정은 마이그레이션 전에 지갑 백업을 생성합니다. 이 백업 파일은 -.legacy.bak로 명명되며 이 지갑의 디렉토리에서 찾을 수 있습니다. 마이그레이션이 잘못될 경우, '지갑 복원' 기능을 통해 백업을 복원할 수 있습니다.</translation>
    
YES: The translation is missing the format specifier for the wallet name and timestamp in the backup file name.
        <source>Migrating the wallet will convert this wallet to one or more descriptor wallets. A new wallet backup will need to be made.
If this wallet contains any watchonly scripts, a new wallet will be created which contains those watchonly scripts.
If this wallet contains any solvable but not watched scripts, a different and new wallet will be created which contains those scripts.

The migration process will create a backup of the wallet before migrating. This backup file will be named &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak and can be found in the directory for this wallet. In the event of an incorrect migration, the backup can be restored with the "Restore Wallet" functionality.</source>
        <translation>지갑을 마이그레이션하면 이 지갑은 하나 이상의 설명자 지갑으로 변환됩니다. 새로운 지갑 백업이 필요합니다. 이 지갑에 watchonly 스크립트가 포함되어 있으면, 해당 watchonly 스크립트를 포함하는 새로운 지갑이 생성됩니다. 해결 가능하지만 관찰되지 않은 스크립트가 포함되어 있으면, 해당 스크립트를 포함하는 다른 새로운 지갑이 생성됩니다.

마이그레이션 과정은 마이그레이션 전에 지갑 백업을 생성합니다. 이 백업 파일은 &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak로 명명되며 이 지갑의 디렉토리에서 찾을 수 있습니다. 마이그레이션이 잘못될 경우, '지갑 복원' 기능을 통해 백업을 복원할 수 있습니다.</translation>
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>외부 서명 지원 없이 컴파일됨 (외부 서명에 필요) 개발자 참고 사항 [from:developer] "외부 서명"은 하드웨어 지갑과 같은 장치를 사용하는 것을 의미합니다.</translation>
    
YES, The translation incorrectly includes the phrase "개발자 참고 사항 [from:developer]" and the extracommment "외부 서명"은 하드웨어 지갑과 같은 장치를 사용하는 것을 의미합니다." in the translation itself. The extracommment is meant to provide context and should not be part of the translated text.

Correct translation: 외부 서명 지원 없이 컴파일됨 (외부 서명에 필요)
```

```
        <source>The label associated with this address list entry</source>
        <translation>현재 선택된 주소 필드의 라벨입니다.</translation>
    
YES, The translation contains erroneous content. The English phrase "The label associated with this address list entry" means "This address list entry's label". The current translation "현재 선택된 주소 필드의 라벨입니다." means "This is the label of the currently selected address field." This is not the same meaning.
The correct translation is: 이 주소 목록 항목에 연결된 라벨
```

```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>본 주소록 입력은 주소와 연계되었습니다.  이것은 보내는 주소들을 위해서만 변경될수 있습니다.</translation>
    
YES: The translation is awkward and grammatically incorrect. The phrase "본 주소록 입력은 주소와 연계되었습니다" literally translates to "This address book entry is associated with an address," which is a bit redundant and doesn't flow well. Also, "이것은 보내는 주소들을 위해서만 변경될수 있습니다" translates to "This can only be changed for sending addresses," which is also awkward phrasing.

A more natural and accurate translation would be:

본 주소록 항목은 주소와 연결되어 있습니다. 보내는 주소에 대해서만 수정할 수 있습니다.
```

```
        <source>Directory already exists. Add %1 if you intend to create a new directory here.</source>
        <translation>폴더가 이미 존재합니다. 새로운 폴더 생성을 원한다면 %1 명령어를 추가하세요.</translation>
    
YES, The translation is problematic because it misinterprets the meaning of "%1". In the original English text, "%1" is likely a placeholder for a command or an argument that the user needs to add to create a new directory. The Korean translation, however, translates "%1" as "명령어" which means "command". This is not necessarily wrong, but it's more likely a placeholder for a specific command to be inserted. The original text is very general, and it's best to keep it that way to avoid potential misunderstandings. Additionally, the translation uses "폴더" which translates to "folder", whereas the English uses "directory". While both are similar, the original uses "directory", so it's best to stick to that term for accuracy.

Correct translation:
디렉토리가 이미 존재합니다. 여기서 새 디렉토리를 만들려면 %1을 추가하세요.
```

```
        <source>Attempting to spend bitcoins that are affected by not-yet-displayed transactions will not be accepted by the network.</source>
        <translation>아직 표시되지 않은 거래의 영향을 받는 비트코인을 사용하려고 하는 것은 네트워크에서 허가되지 않습니다.</translation>
    
YES: The translation uses the word "허가되지" (heoga-doeji) which means "not permitted" or "not licensed". In the context of Bitcoin transactions, a more appropriate word would be "허용되지" (heoyong-doeji) which means "not allowed" or "not accepted".

Corrected translation: 아직 표시되지 않은 거래의 영향을 받는 비트코인을 사용하려고 하는 것은 네트워크에서 허용되지 않습니다.
```

```
        <source>%1 is currently syncing.  It will download headers and blocks from peers and validate them until reaching the tip of the block chain.</source>
        <translation>%1가 현재 동기화 중입니다. 이것은 피어에서 헤더와 블록을 다운로드하고 블록 체인의 끝에 도달 할 때까지 유효성을 검사합니다.</translation>
    
YES. The translation incorrectly uses the pronoun "이것은" (this is) which refers to the subject of the previous clause, but the source text is referring to the process of syncing, not a specific noun.

%1가 현재 동기화 중입니다. 피어로부터 헤더와 블록을 다운로드하고 블록 체인의 최상단까지 유효성을 검사하는 과정입니다.
```

```
        <source>Number of script verification threads</source>
        <translation>스크립트 인증 쓰레드의 개수(V)</translation>
    
YES, The translation is problematic due to unnatural phrasing and the inclusion of "(V)" which is not present in the original text.

The correct translation is:
스크립트 검증 스레드 수
```

```
        <source>Set the number of script verification threads. Negative values correspond to the number of cores you want to leave free to the system.</source>
        <extracomment>Tooltip text for Options window setting that sets the number of script verification threads. Explains that negative values mean to leave these many cores free to the system.</extracomment>
        <translation>스크립트 검증 수명의 숫자를 설정하세요. 음수는 시스템에 묶이지 않는 자유로운 코어의 수를 뜻합니다.</translation>
    
YES - The Korean translation uses "수명" which means "lifespan" or "lifetime" instead of "threads". This is an incorrect translation. The correct translation for "threads" in this context is "스레드".

Correct translation: 스크립트 검증 스레드의 수를 설정하세요. 음수는 시스템에 남겨두고 싶은 코어의 수를 의미합니다.
```

```
        <source>Whether to set subtract fee from amount as default or not.</source>
        <extracomment>Tooltip text for Options window setting that sets subtracting the fee from a sending amount as default.</extracomment>
        <translation>수수료 감면을 초기값으로 할지 혹은 설정하지 않을지를 결정합니다.</translation>
    
YES - The translation does not accurately convey the meaning of the source text. The source text asks about setting a default option for subtracting fees from the amount, while the translation implies deciding whether to *not* set the fee reduction as default. The nuance of "as default or not" is lost.

Correct translation: 수수료를 송금액에서 차감하는 것을 기본값으로 설정할지 여부입니다.
```

```
        <source>Spend unconfirmed change</source>
        <translation>검증되지 않은 잔돈 쓰기 (S)</translation>
    
YES - The translation uses "잔돈" which can be interpreted as "coins" in general rather than "change" specifically in the context of a Bitcoin transaction. The "(S)" at the end is also an unusual addition and doesn't seem to have a clear purpose in this context.

A more accurate translation would be:
검증되지 않은 거스름돈 사용
```

```
        <source>External signer script path</source>
        <translation>외부 서명자 스크립트 경로
 </translation>
    
YES: The translation contains an extraneous space character at the end of the line.
Correct Translation: 외부 서명자 스크립트 경로
```

```
        <source>Connect through SOCKS5 proxy (default proxy):</source>
        <translation>SOCKS5 프록시를 거쳐 연결합니다(C) (기본 프록시):</translation>
    
YES, The translation includes an unnecessary and incorrect character "(C)" after "proxy". The source text does not contain this character.

SOCKS5 프록시를 거쳐 연결합니다 (기본 프록시):
```

```
        <source>Show the icon in the system tray.</source>
        <translation>시스템 트레이에 있는 아이콘 숨기기</translation>
    
YES, The translation is inaccurate. The source text means "Show the icon in the system tray", but the translation means "Hide the icon in the system tray".
The correct translation is "시스템 트레이에 아이콘 표시".
```

```
        <source>Third-party URLs (e.g. a block explorer) that appear in the transactions tab as context menu items. %s in the URL is replaced by transaction hash. Multiple URLs are separated by vertical bar |.</source>
        <translation>내용 메뉴 아이템으로 거래내역 탭이 보이는 제3자 URL (블록익스프로러). URL에 %s는 트랜잭션 해시값으로 대체됩니다. 복수의 URL은 수직항목으로부터 분리됩니다. </translation>
    
YES: The translation uses awkward phrasing and a mistranslation of "vertical bar". The sentence structure also feels unnatural in Korean.

Correct translation: 거래내역 탭에 표시되는 제3자 URL (예: 블록 탐색기)은 맥락 메뉴 항목으로 나타납니다. URL의 %s는 거래 해시값으로 대체됩니다. 여러 URL은 세로 막대(|)로 구분됩니다.
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>외부 서명 지원 없이 컴파일됨 (외부 서명에 필요) 개발자 참고 사항 [from:developer] "외부 서명"은 하드웨어 지갑과 같은 장치를 사용하는 것을 의미합니다.</translation>
    
YES, The translation incorrectly includes the phrase "개발자 참고 사항 [from:developer]" and the extracommment "외부 서명"은 하드웨어 지갑과 같은 장치를 사용하는 것을 의미합니다." in the translation itself. The extracommment is meant to provide context and should not be part of the translated text.

Correct translation: 외부 서명 지원 없이 컴파일됨 (외부 서명에 필요)
```

```
        <source>The configuration file is used to specify advanced user options which override GUI settings. Additionally, any command-line options will override this configuration file.</source>
        <extracomment>Explanatory text about the priority order of instructions considered by client. The order from high to low being: command-line, configuration file, GUI settings.</extracomment>
        <translation>GUI 설정을 우선하는 고급 사용자 옵션을 지정하는 데 사용되는 설정파일 입니다. 추가로 모든 명령 줄 옵션도 이 설정 파일보다 우선시 됩니다.</translation>
    
YES: The translation incorrectly states that command-line options override the configuration file, when the source text states the opposite.
Correct translation: GUI 설정을 무시하는 고급 사용자 옵션을 지정하는 데 사용되는 설정 파일입니다. 추가로 모든 명령줄 옵션은 이 설정 파일보다 우선합니다.
```

```
        <source>Mined balance in watch-only addresses that has not yet matured</source>
        <translation>조회-전용 주소의 채굴된 잔액 중 사용가능하지 않은 금액</translation>
    
YES - The Korean translation for "matured" is incorrect. In the context of Bitcoin, "matured" refers to coins that have been in the wallet for a certain period and are ready to be spent, not just "available".

Correct translation: 조회-전용 주소의 채굴된 잔액 중 아직 사용 가능하지 않은 금액
```

```
        <source>Whether we relay addresses to this peer.</source>
        <extracomment>Tooltip text for the Address Relay field in the peer details area, which displays whether we relay addresses to this peer (Yes/No).</extracomment>
        <translation>이 피어에게 지갑주소를 릴레이할지를 결정합니다.</translation>
    
YES: The translation incorrectly uses "지갑주소" (wallet address) when the context of Bitcoin networks suggests "네트워크 주소" (network address) is more appropriate. Also, the phrasing "결정합니다" (decides) is a bit strong for a tooltip that should indicate a state. A more accurate and neutral translation would be "이 피어에게 주소를 릴레이하는지 여부" (Whether addresses are relayed to this peer).

NO: 이 피어에게 주소를 릴레이하는지 여부
```

```
        <source>Address Relay</source>
        <extracomment>Text title for the Address Relay field in the peer details area, which displays whether we relay addresses to this peer (Yes/No).</extracomment>
        <translation>지갑주소를 릴레이합니다.</translation>
    
YES, The translation provided is inaccurate and misleading. The source text "Address Relay" refers to the relaying of Bitcoin network addresses, not wallet addresses. The translation incorrectly states "지갑주소를 릴레이합니다" which means "Relays wallet addresses".

The correct translation should reflect the relaying of network addresses.

Correct translation: 네트워크 주소 릴레이
```

```
        <source>Addresses Processed</source>
        <extracomment>Text title for the Addresses Processed field in the peer details area, which displays the total number of addresses received from this peer that were processed (excludes addresses that were dropped due to rate-limiting).</extracomment>
        <translation>처리된 지갑</translation>
    
YES, The translation is problematic as it only mentions "wallets" and omits the broader concept of "addresses". It also incorrectly assumes it refers specifically to Bitcoin wallet addresses, when the context implies network addresses as well.

Correct translation: 처리된 주소
```

```
        <source>Addresses Rate-Limited</source>
        <extracomment>Text title for the Addresses Rate-Limited field in the peer details area, which displays the total number of addresses received from this peer that were dropped (not processed) due to rate-limiting.</extracomment>
        <translation>지갑의 Rate제한</translation>
    
YES
The translation "지갑의 Rate제한" (Jigap-ui Rate-Jehan) is not an accurate translation of "Addresses Rate-Limited".
"지갑" means "wallet" and "Rate제한" means "rate limit". Therefore, the translation means "Wallet's Rate Limit", which doesn't capture the meaning of "Addresses Rate-Limited" as described in the context.

The correct translation should be "주소 Rate 제한" (Juso Rate Jehan) or "주소 접근 속도 제한" (Juso Jeopgeun Sokdo Jehan).
"주소" means "address" and "Rate 제한" means "rate limit". The latter option additionally clarifies that it is about the speed of access.

Correct Translation: 주소 Rate 제한
```

```
        <source>Elapsed time since a novel transaction accepted into our mempool was received from this peer.</source>
        <extracomment>Tooltip text for the Last Transaction field in the peer details area.</extracomment>
        <translation>이 피어에서 새 트랜잭션이 수신된 이후 경과된 시간입니다.</translation>
    
YES
The original translation missed the nuance of "mempool" and "accepted into our mempool". The provided translation is a more direct and accurate representation of the source text, conveying that the transaction was *received* from the peer and then *accepted* into the mempool.

Correct translation: 이 피어에서 새 트랜잭션이 메모풀에 받아들여진 이후 경과된 시간입니다.
```

```
        <source>Inbound: initiated by peer</source>
        <extracomment>Explanatory text for an inbound peer connection.</extracomment>
        <translation>시작점 : 동기에 의해 시작됨</translation>
    
YES: The translation is inaccurate and does not convey the intended meaning of the source text in the context of Bitcoin. "Inbound: initiated by peer" refers to a network connection that is being established from an external source (peer) into the user's system. The Korean translation "시작점 : 동기에 의해 시작됨" (Starting point: initiated by motivation) is completely unrelated and nonsensical in this context.

Correct translation: 들어오는 연결: 피어에 의해 시작됨
```

```
        <source>Outbound Manual: added using RPC %1 or %2/%3 configuration options</source>
        <extracomment>Explanatory text for an outbound peer connection that was established manually through one of several methods. The numbered arguments are stand-ins for the methods available to establish manual connections.</extracomment>
        <translation>아웃바운드 매뉴얼 : RPC %1 이나 %2/%3 을 사용해서 환경설정 옵션을 추가</translation>
    
YES: The translation is grammatically incorrect and awkward. The phrase " RPC %1 이나 %2/%3 을 사용해서 환경설정 옵션을 추가" translates to "Added configuration options using RPC %1 or %2/%3". This is not a natural way to express the meaning of the source text.

A more natural and accurate translation would be:

아웃바운드 매뉴얼: RPC %1 또는 %2/%3 구성 옵션을 사용하여 추가됨
```

```
        <source>Outbound Address Fetch: short-lived, for soliciting addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to request addresses from a peer.</extracomment>
        <translation>아웃바운드 주소 가져오기: 단기, 주소 요청용
 </translation>
    
YES - The translation includes an unnecessary trailing space.
아웃바운드 주소 가져오기: 단기, 주소 요청용
```

```
        <source>Copy label</source>
        <translation>복사  라벨</translation>
    
YES, The spacing between "복사" and "라벨" is incorrect. The correct translation is "복사 라벨".
```

```
        <source>Copy amount</source>
        <translation>복사  금액</translation>
    
YES, The spacing between "복사" and "금액" is incorrect. It should be "복사 금액".
NO
```

```
        <source>Request payment to …</source>
        <translation>에게 지불을 요청</translation>
    
YES, The translation is missing the object "payment to" from the source text. The correct translation should include this information to convey the meaning of the original sentence.
에게 지불을 요청하세요.
```

```
        <source>Verify</source>
        <translation>승인</translation>
    
YES, The translation is inaccurate. In the context of Bitcoin, "Verify" typically translates to "확인" or "검증" in Korean, not "승인" which means "Approve" or "Authorize".

Correct translation: 확인
```

```
        <source>Custom change address</source>
        <translation>주소 변경</translation>
    
YES, The translation is incorrect. It translates "Custom change address" as "address change" which is not the same meaning. The correct translation should be "맞춤 변경 주소".
 맞춤 변경 주소
```

```
        <source>Using the fallbackfee can result in sending a transaction that will take several hours or days (or never) to confirm. Consider choosing your fee manually or wait until you have validated the complete chain.</source>
        <translation>고장 대체 수수료를 사용하게 될 경우 보낸 거래가 승인이 완료 될 때까지 몇 시간 혹은 몇 일 (혹은 영원히) 이 걸릴 수 있습니다. 수동으로 수수료를 선택하거나 전체 체인의 유효성이 검증될 때까지 기다리십시오.</translation>
    
YES. The translation contains a mistranslation of "fallbackfee" and "validated the complete chain".

The correct translation for "fallbackfee" in this context would be "기본 수수료" (basic fee) or "대체 수수료" (alternative fee). "고장 대체 수수료" (broken alternative fee) does not make sense.

The correct translation for "validated the complete chain" would be "완전한 체인을 검증할 때까지" (until the complete chain is validated) or "블록체인 전체가 동기화될 때까지" (until the entire blockchain is synchronized). "전체 체인의 유효성이 검증될 때까지" is grammatically awkward and not idiomatic.

Corrected translation:
기본 수수료를 사용하면 거래가 승인될 때까지 몇 시간, 며칠 또는 영원히 걸릴 수 있습니다. 수동으로 수수료를 선택하거나 전체 체인이 동기화될 때까지 기다리십시오.
```

```
        <source>Create Unsigned</source>
        <translation>사인되지 않은 것을 생성(e)</translation>
    
YES, The translation is problematic. The Korean word "생성(e)" is grammatically incorrect and doesn't fit the context of creating something. It should be "생성" or "생성하기". Also, the English phrase "Create Unsigned" usually refers to creating an unsigned transaction, so a more natural translation would be "서명되지 않은 거래 생성".

NO
서명되지 않은 것 생성
```

```
        <source>Please, review your transaction. You can create and send this transaction or create a Partially Signed Bitcoin Transaction (PSBT), which you can save or copy and then sign with, e.g., an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can send their transaction or create a PSBT. This string is displayed when both private keys and PSBT controls are enabled.</extracomment>
        <translation>당신의 트랜잭션을 검토하세요. 당신은 트랜잭션을 생성하고 보낼 수 있습니다. 혹은 부분적으로 서명된 비트코인 트랜잭션 (PSBT, Partially Signed Bitcoin Transaction)을 생성하고, 저장하거나 복사하여 오프라인 %1지갑으로 서명할수도 있습니다. PSBT가 적용되는 하드월렛으로 서명할 수도 있습니다. </translation>
    
YES, The translation is problematic because it incorrectly translates "wallet" as "지갑" in the first instance and then incorrectly translates "wallet" as "하드월렛" in the second instance. The phrase "offline %1 wallet" should be translated consistently.

Correct translation: 당신의 트랜잭션을 검토하세요. 당신은 트랜잭션을 생성하고 보낼 수 있습니다. 혹은 부분적으로 서명된 비트코인 트랜잭션 (PSBT, Partially Signed Bitcoin Transaction)을 생성하고, 저장하거나 복사하여 오프라인 %1지갑으로 서명할수도 있습니다. PSBT가 적용되는 하드웨어 지갑으로 서명할 수도 있습니다.
```

```
        <source>Not signalling Replace-By-Fee, BIP-125.</source>
        <translation>'수수료로-대체', BIP-125를 지원하지 않습니다.</translation>
    
YES, The translation is problematic because it incorrectly translates "Replace-By-Fee" as "수수료로-대체" which means "as a fee-replacement". The correct translation for "Replace-By-Fee" in this context would be "대체-수수료" which means "replacement-fee".

NO, '수수료로-대체', BIP-125를 지원하지 않습니다.
```

```
        <source>Warning: Unknown change address</source>
        <translation>경고: 알려지지 않은 주소 변경입니다</translation>
    
YES, The translation is inaccurate and creates a nonsensical sentence in Korean. The original English "Unknown change address" refers to a Bitcoin address that is not recognized or known. The Korean translation "알려지지 않은 주소 변경입니다" literally means "It is an unknown address change," which doesn't convey the intended meaning in the context of Bitcoin addresses.

The correct translation should be:

경고: 알 수 없는 변경 주소
```

```
        <source>Subtract fee from amount</source>
        <translation>송금액에서 수수료 공제(U)</translation>
    
YES, The translation is problematic because it includes an unnecessary parenthetical "(U)" which is likely a remnant of an annotation or a placeholder that should not be present in the final translation.

Correct translation: 송금액에서 수수료 공제
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1/미확인</translation>
    
YES: The Korean translation for "unconfirmed" is incorrect. "미확인" (mihwagin) means "unidentified" or "unknown". The correct translation for "unconfirmed" in the context of Bitcoin transactions is "미확인된" (mihwagindoen) or "미승인" (miseungin).

Correct translation: %1/미확인된
```

```
        <source>Received with</source>
        <translation>받은 주소 :</translation>
    
YES: The translation is inaccurate and misleading. In the context of Bitcoin, "Received with" typically refers to the method or the origin of receiving the Bitcoin, not necessarily a specific address. The Korean translation implies "Received from address:", which is not a direct or accurate translation of the source text.

A more accurate translation would depend on the specific nuance intended by "Received with." If it means received *from* a particular entity or method, a more appropriate Korean phrase would be needed. However, if it's simply an indicator that a transaction was received, a more neutral phrasing would be better.

Given the ambiguity and the problematic nature of the provided translation, it's difficult to give a single perfect translation without more context. However, if the intention is to indicate receipt in a general sense, a better translation could be:

받음 (Badeum - Receipt) or 수신 (Susin - Reception)

If it's meant to imply the source of the receipt, a more informative translation would be required. Since the provided translation is clearly wrong, we flag it as problematic.

Correct Translation: 수신: (Susin:) or 받은: (Badeun:)
```

```
        <source>Received from</source>
        <translation>보낸 주소 :</translation>
    
YES, The translation uses "보낸 주소" which translates to "Sent address" or "Sender's address". The source text "Received from" implies the origin of the transaction, which would be the sender's address. However, the direct translation is "보낸 사람으로부터" (from the sender) or "발신자로부터" (from the sender). "보낸 주소" is also acceptable in the context of Bitcoin transactions, as it refers to the address from which the Bitcoin was sent. However, a more natural and direct translation would be "받은 주소" which means "Received address" or "Sender address", depending on the context. Since the context is Bitcoin, it's likely referring to the address from which the funds were sent. If the intention is to refer to the address that *received* the funds, then it would be "받은 사람의 주소" or simply "받는 주소". Given the common phrasing in Bitcoin transactions, "보낸 사람의 주소" (Sender's address) or "출처 주소" (Source address) would be more appropriate. However, in many UI contexts, "보낸 주소" can imply "the address that sent it". Let's consider the alternatives.

If "Received from" refers to the originating wallet address that sent the Bitcoin, then a more accurate translation would be:
"보낸 사람 주소" (Sender address) or "출처 주소" (Source address).

However, if we interpret "Received from" as indicating the entity from which something was received, and in a Bitcoin context, that would be the sending address, then "보낸 주소" (Sent address) is understandable, though not the most literal translation of "Received from".

Let's consider a common user interface phrasing for Bitcoin. When you receive Bitcoin, you often see "Received from [address]". In this context, "보낸 주소" (Sent address) implies the address that sent the funds.

A more direct and perhaps clearer translation would be:
"출처 주소 :" (Source address :) or "발신 주소 :" (Sender address :)

Let's assume the intended meaning is to display the address of the sender.

Correct translation: 출처 주소 :
```

```
        <source>Received with</source>
        <translation>받은 주소 :</translation>
    
YES: The translation is inaccurate and misleading. In the context of Bitcoin, "Received with" typically refers to the method or the origin of receiving the Bitcoin, not necessarily a specific address. The Korean translation implies "Received from address:", which is not a direct or accurate translation of the source text.

A more accurate translation would depend on the specific nuance intended by "Received with." If it means received *from* a particular entity or method, a more appropriate Korean phrase would be needed. However, if it's simply an indicator that a transaction was received, a more neutral phrasing would be better.

Given the ambiguity and the problematic nature of the provided translation, it's difficult to give a single perfect translation without more context. However, if the intention is to indicate receipt in a general sense, a better translation could be:

받음 (Badeum - Receipt) or 수신 (Susin - Reception)

If it's meant to imply the source of the receipt, a more informative translation would be required. Since the provided translation is clearly wrong, we flag it as problematic.

Correct Translation: 수신: (Susin:) or 받은: (Badeun:)
```

```
        <source>Copy label</source>
        <translation>복사  라벨</translation>
    
YES, The spacing between "복사" and "라벨" is incorrect. The correct translation is "복사 라벨".
```

```
        <source>Copy amount</source>
        <translation>복사  금액</translation>
    
YES, The spacing between "복사" and "금액" is incorrect. It should be "복사 금액".
NO
```

```
        <source>Copy transaction ID</source>
        <translation>복사 트랜잭션  아이디</translation>
    
YES, The translation is problematic because of spacing.
Correct translation: 복사 트랜잭션 ID
```

```
        <source>Copy raw transaction</source>
        <translation>처리되지 않은 트랜잭션 복사</translation>
    
YES, The translation is problematic. The Korean word for "raw" in this context should be "원시" or "가공되지 않은" instead of "처리되지 않은".

Correct translation: 원시 트랜잭션 복사
```

```
        <source>%s corrupt. Try using the wallet tool bitcoin-wallet to salvage or restoring a backup.</source>
        <translation>%s가 손상되었습니다. '비트 코인-지갑'을 사용하여 백업을 구제하거나 복원하십시오.</translation>
    
YES, The translation is problematic because it incorrectly translates "salvage or restoring a backup" as "백업을 구제하거나 복원하십시오". The correct translation should be "백업을 복구하거나 복원하십시오".

%s 손상되었습니다. '비트 코인-지갑' 도구를 사용하여 백업을 복구하거나 복원해 보십시오.
```

```
        <source>Cannot upgrade a non HD split wallet from version %i to version %i without upgrading to support pre-split keypool. Please use version %i or no version specified.</source>
        <translation>사전분리 키풀를 지원하기 위해서 업그레이드 하지 않고는 Non HD split 지갑의 %i버젼을 %i버젼으로 업그레이드 할 수 없습니다. %i버젼을 활용하거나 구체화되지 않은 버젼을 활용하세요.</translation>
    
YES: The translation is problematic due to awkward phrasing and a mistranslation of "no version specified." The Korean sentence structure is unnatural and the phrase "구체화되지 않은 버젼" is an incorrect translation of "no version specified."

Correct Translation: HD split이 아닌 지갑을 버전 %i에서 버전 %i로 업그레이드하려면 사전 분할 키풀 지원으로 먼저 업그레이드해야 합니다. 버전 %i 또는 버전을 지정하지 않은 상태로 진행해 주십시오.
```

```
        <source>Invalid or corrupt peers.dat (%s). If you believe this is a bug, please report it to %s. As a workaround, you can move the file (%s) out of the way (rename, move, or delete) to have a new one created on the next start.</source>
        <translation>유효하지 않거나 손상된 peers.dat(%s). 만약 이게 버그인 경우에, %s이쪽으로 리포트해주세요.  새로 만들어서 시작하기 위한 해결방법으로 %s파일을 옮길 수 있습니다. (이름 재설정, 파일 옮기기 혹은 삭제).</translation>
    
YES: The Korean translation incorrectly uses "이쪽으로" which translates to "towards this side" or "in this direction", and should be replaced with a more appropriate preposition or phrasing to indicate reporting to a specific entity or place. Also, the phrasing "새로 만들어서 시작하기 위한 해결방법으로" is a bit clunky and could be more natural.

Corrected translation: 유효하지 않거나 손상된 peers.dat(%s). 만약 이게 버그인 경우, %s에 보고해주세요. 해결 방법으로, 새 파일이 시작 시 생성되도록 해당 파일(%s)을 다른 곳으로 옮기십시오(이름 변경, 이동 또는 삭제).
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>하나 이상의 양파 바인딩 주소가 제공됩니다. 자동으로 생성 된 Tor onion 서비스에 %s 사용.</translation>
    
YES: The translation of "onion bind address" to "양파 바인딩 주소" is too literal and doesn't convey the intended meaning of a Tor onion service bind address. A more appropriate translation would refer to the Tor network or onion services.

Correct translation: Tor onion 서비스에 자동으로 생성된 바인딩 주소로 %s를 사용합니다.
```

```
        <source>No wallet file format provided. To use createfromdump, -format=&lt;format&gt; must be provided.</source>
        <translation>shshhdchb bdfjj fb  rciivfjb doffbfbdjdj</translation>
    
YES, The translation appears to be nonsensical and not a valid Korean translation. It is likely machine-generated garbage text. The correct translation should convey the meaning of the English source text.

Correct translation: 지갑 파일 형식이 제공되지 않았습니다. createfromdump를 사용하려면 -format=<형식>을 제공해야 합니다.
```

```
        <source>Cannot set -forcednsseed to true when setting -dnsseed to false.</source>
        <translation>naravfbj. dufb jdncnlfs. jx dhcji djc d jcbc jdnbfbicb </translation>
    
YES, The translation is completely nonsensical and does not resemble Korean in any way. It appears to be a random string of characters.

Correct translation: -dnsseed가 false일 때 -forcednsseed를 true로 설정할 수 없습니다.
```

```
        <source>Dump file %s does not exist.</source>
        <translation>파일 버리기 %s 존재 안함</translation>
    
YES - The Korean translation is grammatically incorrect and unnatural. The correct translation should be "덤프 파일 %s가 존재하지 않습니다." (Deompeu pail %s-ga jonjaehaji anseumnida.)
```

```
        <source>Error creating %s</source>
        <translation>만들기 오류 %s</translation>
    
YES
The translation is unnatural and grammatically incorrect in Korean. The word order is reversed.

Error creating %s
만들기 오류 %s

Correct translation:
%s 만들기 오류
```

```
        <source>Failed to verify database</source>
        <translation>데이터베이스를 검증 실패</translation>
    
YES, The translation is grammatically incorrect. The correct translation should be "데이터베이스 검증 실패" or "데이터베이스 검증에 실패했습니다".
데이터베이스 검증 실패
```

```
        <source>Invalid netmask specified in -whitelist: '%s'</source>
        <translation>유효하지 않은 넷마스크가 -whitelist: '%s" 를 통해 지정됨</translation>
    
YES, The translation incorrectly places the colon and single quote. The correct translation is:
유효하지 않은 넷마스크가 -whitelist: '%s'에 지정되었습니다.
```

```
        <source>SQLiteDatabase: Failed to prepare statement to verify database: %s</source>
        <translation>에스큐엘라이트 데이터베이스 : 데이터베이스를 확인하는 실행문 준비에 실패하였습니다 : %s.</translation>
    
YES - The translation is problematic due to a trailing period after the format specifier. The correct translation should not have this period.
에스큐엘라이트 데이터베이스 : 데이터베이스를 확인하는 실행문 준비에 실패하였습니다 : %s
```

```
        <source>SQLiteDatabase: Failed to read database verification error: %s</source>
        <translation>에스큐엘라이트 데이터베이스 : 데이터베이스 읽기를 실패하였습니다: %s</translation>
    
YES, The translation is problematic. The phrase "데이터베이스 읽기를 실패하였습니다" is not a natural way to express the failure to read a database in Korean. A more natural translation would be "데이터베이스를 읽는 데 실패했습니다" or "데이터베이스 읽기 오류가 발생했습니다". Additionally, the source text includes "verification error", which is not reflected in the translation.

Here's the corrected translation:
SQLiteDatabase: Failed to read database verification error: %s -> SQLite 데이터베이스: 데이터베이스 검증 읽기 오류: %s
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>거래액은 반드시 0보다 큰 값이어야 합니다.</translation>
    
YES, The translation is problematic because it states that transaction amounts must be greater than 0, while the original English text states that transaction amounts must not be negative. Negative transaction amounts are not allowed, but zero transaction amounts are.
The correct translation should be: 거래액은 음수이면 안 됩니다.
```

```
        <source>Unknown -blockfilterindex value %s.</source>
        <translation>알 수 없는 -blockfileterindex 값 %s.</translation>
    
YES - The Korean translation contains a typo in the word "blockfilterindex". The correct spelling should be "blockfilterindex".

알 수 없는 -blockfilterindex 값 %s.
```

```
        <source>User Agent comment (%s) contains unsafe characters.</source>
        <translation>사용자 정의 코멘트 (%s)에 안전하지 못한 글자가 포함되어 있습니다.</translation>
    
YES, The translation incorrectly translates "User Agent comment" to "사용자 정의 코멘트" (user-defined comment). The correct translation should reflect "User Agent comment".
사용자 에이전트 코멘트 (%s)에 안전하지 못한 글자가 포함되어 있습니다.
```
</details>
