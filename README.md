# RTK3

* KOEI Kou Shibusawa History Simulation series
* Romance of the Three Kingdoms 3
* English
* DOS
* Character names fully^ corrected 33 years after release


## Background

Originally released in 1992, Romance of the Three Kingdoms 3（三国志III, "RTK3"）is one of KOEI's history simulation classics. The DOS edition of RTK3 came out in Japanese, Korean, English, and Chinese. Unfortunately, the English version was plagued by numerous errors and inconsistencies across the names of nearly 20 percent of the 500+ characters featured in the game.

To restore the history simulation game's historical^^ accuracy, files in this repository apply corrections to all known errors in the English names of KOEI's RTK3 characters. There are no alterations to characters' abilities or other attributes.


## Usage instructions and caveats

Download the six (6) .CIM files. Replace the originals with the downloaded files.

Name corrections do __not__ apply to previously created RTK3 save data or further saves of that data. Let go of it and start fresh.

To run RTK3 for DOS on a modern-day computer, emulation is required. See [DOSBox-X](https://dosbox-x.com/) to get started. For the best emulation experience, set _autofit_ and _doublescan_ to _false_ in the DOSBox-X configurations.


## Availability of RTK3 and other KOEI classics

These .CIM files are __not__ the RTK3 software in its entirety. A copy of English RTK3 for DOS is required as a base. The original software can be found on various archives and [*abandonware*](https://en.wikipedia.org/wiki/Abandonware) sites.

Clearly, none of KOEI's *native* DOS classics are available for sale through official channels anymore. However, [KOEI Tecmo](https://www.koeitecmo.co.jp/) does sell the Windows remake of RTK3 on Steam. The Steam edition of RTK3 is the same game as RTK3 for DOS, featuring identical content and mechanics, although it comes with a very different look and feel, loses the DOS-era nostalgia and is available only in Japanese.

KOEI appears to have erased their own endeavours to localise the early Kou Shibusawa history simulation titles that were once released in English, including RTK 1 through 3, Nobunaga's Ambition（信長の野望）, Nobunaga's Ambition 2（信長の野望：戦国群雄伝）, Bandit Kings of Ancient China（水滸伝：天命の誓い）, L'Empereur（ランペルール）, Genghis Khan 2（元朝秘史：蒼き狼と白き牝鹿）, and Uncharted Waters: New Horizons（大航海時代II）. KOEI has, however, revived every one of these DOS games on Steam, many of them unmodified; but again, solely in Japanese.

The only option for newcomers who are keen to "own" a copy of RTK3 for DOS, in any language, is to buy the Japanese-language Windows Steam remake of RTK3. But with or without a Steam licence, __there is no product support for RTK3 DOS whatsoever, not from KOEI Tecmo, not from anyone__.


## Method and results of belated quality control

What began as a few ad-hoc fixes here and there turned into a sweeping audit, something KOEI neglected to do back in 1992. Disappointingly, a wide variety of errors were found, ranging from mix-ups caused by similar-looking Kanji, to inconsistent casing, to suspected guesswork, to incorrectly recognised multi-syllable surnames, to apparent slips on the keyboard, to seemingly deliberate flippancy that cannot be explained otherwise.

The resulting audit utilised the six visible ability attributes of each RTK3 character: Combat (War), Intelligence, Politics, Charm, Army Command, and Naval Command. Initially based on a moderately accurate [list of KOEI RTK3 warriors in Japanese](https://gcgx.games/sangokushi/3/warriors.html), unique hexadecimal-converted attribute combinations ("signatures") were generated and validated against the English RTK3 binaries for identification, row by row and scenario by scenario. In the end, errors and inaccuracies were found on both sides, that is, the documentation and the software.

Included in this repository is corrected data across all 532 RTK3 characters in CSV format, most likely the only complete multilingual reference of its kind on the Internet.

For KOEI's English RTK3, the outcome of this audit is a milestone: __What is featured in the story is documented, and what is documented is actually found in the software.__

Corrections to the original RTK3 software have been made as follows:

* Ahui Nan 阿会喃 あかいなん (was A Huinan)
* Cai Yong 蔡邕 さいよう (was Cui Yang)
* Cao Xi 曹羲 そうぎ (was Cao Yi)
* Cao Xiong 曹熊 そうゆう (was Cao Xong) ^^^
* Cen Hun 岑昏 しんこん (was Qin Hun)
* Chen Qun 陳羣 ちんぐん (was Chen Wei)
* Chen Shi 陳式 ちんしょく (was Cheng Shi) ^^^
* Chen Tai 陳泰 ちんたい (was Chen Ta) ^^^
* Chen Ying 陳応 ちんおう (was Chen Yin) ^^^
* Chunyu Qiong 淳于瓊 じゅんうけい (was Chun Yuqiong and Chunyu huan) ^^^
* Dong Heng 董衡 とうこう (was Dong Wei) ^^^
* Dongtuna 董荼奴 とうとな (was Dong Tonu and Dong Tujie) ^^^^
* Dousi Wang 朶思王 だしおう (was Dou Siwang)
* Fu Rong 傅彤 ふとう (was Fu Tong)
* Fu Xun 傅巽 ふそん (was Fu Yi)
* Gao Ding 高定 こうてい (was Dao Ding) ^^^
* Gongsun Yuan 公孫淵 こうそんえん (was Gongsun Yun) ^^^
* Guanqiu Jian 毋丘倹 かんきゅうけん (was Mu Qiujian and Muqiu Jian) ^^^
* Guo Meng 郭萌 かくぼう (was Hao Meng)
* Han Juzi 韓莒子 かんきょし (was Hanju Zi) ^^^
* Han Song 韓嵩 かんすう (was Han Gao) ^^^
* Han Xian 韓暹 かんせん (was Han Xuan) ^^^
* Hao Zhao 郝昭 かくしょう (was Hao Shao) ^^^
* Hu Che'er 胡車児 こしゃじ (was Hu Cheer) ^^^^
* Hua Xiong 華雄 かゆう (was Hua Xong)
* Huang Quan 黄権 こうけん (was Lei Quan) ^^^
* Huangfu Song 皇甫嵩 こうほすう (was Huangpu Song)
* Jiang Yiqu 蔣義渠 しょうぎきょ (was Jian Yiqu) ^^^
* Jinhuan Sanjie 金環三結（金環結）きんかんけつ (was Jin Huanjie)
* Ju Gu 沮鵠 そこく (was Ju Hu)
* Kong Zhou 孔伷 こうちゅう (was Kong Qiu)
* Kuai Liang 蒯良 かいりょう (was Kuai Lang) ^^^
* Li Hui 李恢 りかい (was Li Hiu) ^^^
* Li Kan 李堪 りかん (was Li Can) ^^^
* Li Xun 李暹 りせん (was Li Xian) ^^^
* Liang Xing 梁興 りょうこう (was Liang Yu)
* Liu Bao 劉豹 りゅうひょう (was Liu tko) ^^^
* Liu Fu 柳甫 りゅうほ (was Liu Pu) ^^^
* Liu Shan 劉禅 りゅうぜん (was Liu Chan)
* Liu Zong 劉琮 りゅうそう (was Liu Cong)
* Lu Ji 陸績 りくせき (was Lu Xu) ^^^
* Lu Jian 呂建 りょけん (was Liu Jian) ^^^
* Man Chong 満寵 まんちょう (was Man Pang) ^^^
* Mi Zhu 糜竺 びじく (was Mi Lan in some scenarios)
* Pan Jun 潘濬 はんしゅん (was Pan Rui) ^^^
* Qiao Rui 橋蕤 きょうずい (was Qiao Zi)
* Qu Yi 麴義 きくぎ (was Ju Yi) ^^^
* Shamo Ke 沙摩可 しゃまか (was Sha Moke and Shame Ke)
* Shang Ju 尚挙 しょうきょ (was Shang Quan)
* Shen Pei 審配 しんぱい (was Pan Pei) ^^^
* Shen Rong 審栄 しんえい (was Pan Rong) ^^^
* Shen Ying 沈瑩 しんえい (was Chen Ying and Sheng Ying) ^^^
* Sima Yi 司馬懿,しばい (was Sima yi) ^^^
* Song Bao 宋宝 そうほう (was Zong Bao)
* Sun Ji 孫冀 そんき (was Sun Yi, War Ability 74) ^^^
* Sun Yi 孫翊 そんよく (was Sun Xu)
* Taishi Ci 太史慈 たいしじ (was Tai Shici) ^^^
* Tan Xiong 譚雄 たんゆう (was Tan Xong) ^^^
* Wang Fu 王甫 おうほ (was Wang Pu)
* Wen Ping 文聘 ぶんぺい (was Wen Pin)
* Xiahou Dun 夏侯惇 かこうとん (was Xiahou Chun) ^^^
* Xiahou En 夏侯恩 かこうおん (was Xiahou en) ^^^
* Xiahou Yuan 夏侯淵 かこうえん (was Xiahou yuan) ^^^
* Xu Zhu 許褚 きょちょ (was Xu Chu)
* Xue Ti 薛悌 せつてい (was Xue Di) ^^^
* Xue Zong 薛綜 せつそう (was Xue Zhong) ^^^
* Xun Chen 荀諶 じゅんしん (was Xun Xin) ^^^
* Yang Bo 楊柏 ようはく (was Yang Bai)
* Yang Chou 楊醜 ようしゅう (was Yang CHou) ^^^
* Yang Fu 楊阜 ようふ (was Yang Bu) ^^^
* Yang Huai 楊懐 ようかい (was Yang Yi) ^^^
* Yin Feng 尹奉 いんほう (was Yen Feng) ^^^
* Yin Mo 尹黙 いんもく (was Yin Ran) ^^^
* Yu Mi 于糜 うび (was Gan Mi)
* Yue Chen 楽綝 がくちん (was Yue Lin)
* Zang Ba 藏覇 ぞうは (was Zhang Ba) ^^^
* Ze Rong 笮融 さくゆう (was Cai Rong)
* Zhang Cheng 張承 ちょうしょう (was Zhan Cheng) ^^^
* Zhang Kai 張闓 ちょうかい (was Zhang Yi, War Ability 59)
* Zhang Xiu 張繡 ちょうしゅう (was Zhang Xiao)
* Zhang Yi 張顗 ちょうぎ (was Zhang Kai, War Ability 67)
* Zhao Cen 趙岑 ちょうしん (was Zhang Cen)
* Zhao Qu 趙衢 ちょうく (was Zhao Wei) ^^^
* Zhou Tai 周泰 しゅうたい (was Zhou Dai) ^^^
* Zhou Xin 周昕 しゅうきん (was Zhou Jin) ^^^
* Zhu Jun 朱儁 しゅしゅん (was Zhu Xiu) ^^^
* Zhu Zhi 朱治 しゅち (was Zhu Zi) ^^^
* Zhuge Ke 諸葛恪 しょかつかく (was Zhuge Luo) ^^^


## Notes

^ Further corrections arising from oversight or a different method are not ruled out.

^^ 'Fictional' may be more accurate, since RTK（三国志演義）itself is a history-inspired fiction.

^^^ Errors were found in some, not all, of the scenarios.

^^^^ Widely accepted alternate spellings exist.
