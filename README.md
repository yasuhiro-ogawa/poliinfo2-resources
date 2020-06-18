# poliinfo2-resources

## minutes_tokyo.json
minutes_tokyo.json は，Pref13_tokyo.json の内容を発言ごとに分割したデータです．
詳細は minutes_tokyo.md をご覧下さい．

## name2role.json および role2name.json

name2role.json と role2name.json は，Pref13_tokyo.json (都議会会議録)中での Speaker の値(name)と，都議会だよりから変換した train1.json などにおける AnswerSpeaker の値(role)との間で変換を行うためのデータです．
なお，日付によって対応が変化するため，key の値には日付も含めます．
例えば name2role.json の key は"2011-06-23:中井敬三" のような形式になります．
role2name.json の場合は "2011-06-23:港湾局長" のような形式になります．
