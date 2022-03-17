# ASE-
## 大腸菌や乳酸菌といった現存生物のデータ1000個のアライメントファイルとそれに対応するtreeファイルを読みこみ、それらの生物種の祖先とされる配列の座位ごとの確率分布を出力するツールである。
### VS codeかVisual Studioで同じディレクトリ内にアライメントファイル(BLAT_data_upper1000_sequence_remove_gap_10percent_211124.a2m)と系統樹ファイル(BLAT_data_upper1000_sequence_remove_gap_10percent_include_root_211124.a2m.treefile)とソースコード(out_probability_ancestArray.cpp)を入れ実装すれば確率分布(BLAT_upper1001_remove_gap10_seq.txt)が得られる。この確率分布を元に算出した祖先最尤配列を以下に示す。

-----LE---GGRLGVAALD-ETGRRLGYRADERFPMCSTFKLLLAAAVLQRVD--GKL K L D R P I P Y - - - D L - D - A P - - - - - V - - G M T V A E L C E A A I Q L S D N T A A N L L L K L V G G P A G L T A Y L R S L G D E V T R L D R T E P E L - - - - - - D P R D T T T P A A M L K L L R K L L L G D A L S P A S K Q Q L K D W L I G T T T G P N R I R A G L P A G W – V G H K T G S G G G A T N D-V G I I W P P G G - P I L L A V Y T T G S - - - - A G R D A V I A E V A R I V – 
