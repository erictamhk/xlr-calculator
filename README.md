# Xiao Liu Ren Lunar Calculator / 小六壬農曆計算器

This web application calculates Xiao Liu Ren (小六壬) divination results based on the current lunar date and time. It displays the positions of the month, day, and hour within the six palaces and provides brief interpretations.

本網頁應用程式根據當前的農曆日期和時間計算小六壬的占卜結果。 它顯示月、日、時在六個宮位中的位置，並提供簡要的解釋。

## What is Xiao Liu Ren? / 什麼是小六壬？

Xiao Liu Ren (小六壬), also known as "Six Secret Methods," is a simple yet effective form of Chinese divination. It's often used for quick predictions and decision-making. Unlike more complex systems like I Ching, Xiao Liu Ren is easy to learn and apply. It relies on calculating positions within a cycle of six "palaces" to provide insights.

小六壬，又稱“六神課”，是一種簡單而有效的中國占卜術。 它通常用於快速預測和決策。 與易經等更複雜的系統不同，小六壬易於學習和應用。 它依靠計算六個“宮位”週期中的位置來提供見解。

## The Six Palaces / 六個宮位

The six palaces of Xiao Liu Ren are:

*   **大安 (Dà Ān) - Great Peace:** Represents stability, security, and good fortune. Things are generally going well. / 代表穩定、安全和好運。 事情總體上進展順利。
*   **留連 (Liú Lián) - Lingering Connection:** Indicates delays, obstacles, and things taking longer than expected. Be patient and persistent. / 表示延遲、障礙以及事情比預期需要更長的時間。 請耐心和堅持。
*   **速喜 (Sù Xǐ) - Speedy Joy:** Signifies good news, quick success, and joyful events. Take advantage of opportunities. / 預示著好消息、快速成功和歡樂的事件。 抓住機會。
*   **赤口 (Chì Kǒu) - Red Mouth:** Warns of arguments, gossip, and potential conflicts. Be careful with your words and actions. / 警告爭論、八卦和潛在的衝突。 小心你的言行。
*   **小吉 (Xiǎo Jí) - Small Fortune:** Suggests minor good luck, small gains, and general well-being. A positive but not overwhelming outcome. / 預示著小的好運、小的收穫和普遍的幸福。 一個積極但並不壓倒性的結果。
*   **空亡 (Kōng Wáng) - Emptiness/Void:** Represents uncertainty, lack of clarity, and potential loss. Proceed with caution and avoid major decisions. / 代表不確定性、缺乏清晰度以及潛在的損失。 謹慎行事，避免重大決定。

## How the Calculator Works / 計算機如何運作

This calculator uses the current lunar month, day, and hour to determine the positions within the six palaces. The calculation method is as follows:

本計算器使用當前的農曆月、日、時來確定六個宮位中的位置。 計算方法如下：

1.  **Determine the Lunar Month / 確定農曆月份:** The lunar month (1-12) is used as the starting point. / 農曆月份 (1-12) 用作起點。
2.  **Determine the Lunar Day / 確定農曆日期:** Starting from the month's position, count forward the number of days in the lunar month. The final position is the day's position. / 從月份的位置開始，向前數農曆月份的天數。 最後的位置是日期的位置。
3.  **Determine the Lunar Hour / 確定農曆時辰:** Starting from the day's position, count forward the number of hours in the lunar day (using the traditional Chinese system of 12 two-hour periods). The final position is the hour's position. / 從日期的位置開始，向前數農曆時辰（使用中國傳統的 12 個時辰系統）。 最後的位置是時辰的位置。

The resulting positions of the month, day, and hour within the six palaces provide the basis for the divination.

月、日、時在六個宮位中的最終位置構成了占卜的基礎。

## How to Use the Calculator / 如何使用計算機

1.  Simply open the `index.html` file in your web browser. / 只需在您的網絡瀏覽器中打開 `index.html` 文件。
2.  The calculator automatically retrieves the current lunar date and time. / 計算機會自動檢索當前的農曆日期和時間。
3.  The results are displayed, showing the positions of the month, day, and hour within the six palaces (大安, 留連, 速喜, 赤口, 小吉, 空亡). / 結果會顯示出來，顯示月、日、時在六個宮位（大安、留連、速喜、赤口、小吉、空亡）中的位置。
4.  A brief interpretation of each palace is provided to give you a basic understanding of the divination. / 提供每個宮位的簡要解釋，讓您對占卜有一個基本的了解。

## Example / 例子

Let's say the current lunar date is:

假設當前的農曆日期是：

*   Month: 3 / 月：3
*   Day: 15 / 日：15
*   Hour: 7 (午時 - Wǔ Shí, 11:00 AM - 1:00 PM) / 時：7 (午時 - Wǔ Shí, 上午 11:00 - 下午 1:00)

The calculator might show the following results:

計算器可能會顯示以下結果：

*   Month: 速喜 (Sù Xǐ)
*   Day: 赤口 (Chì Kǒu)
*   Hour: 小吉 (Xiǎo Jí)

This would suggest a generally positive outlook for the month (速喜), but potential for conflict or arguments on that particular day (赤口), with a small amount of good fortune during that hour (小吉).

這表明本月總體前景看好（速喜），但當天可能存在衝突或爭論（赤口），並且在該時辰會有少量的好運（小吉）。

## Disclaimer / 免責聲明

Xiao Liu Ren is a traditional divination method and should be used for entertainment purposes only. The interpretations provided by this calculator are simplified and should not be taken as definitive predictions.

小六壬是一種傳統的占卜方法，僅應用於娛樂目的。 本計算器提供的解釋經過簡化，不應被視為明確的預測。

## Built With / 使用技術

*   HTML
*   CSS
*   JavaScript
