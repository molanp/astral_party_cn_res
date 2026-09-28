# 星引擎 Party 美术资源

资源概览

1. char_names.json 35 角色 id->中文名 (\_cfg/Character.bin f1=id,f4=name_sid + STRCharacter.bin)
2. map_names.json 24 地图 id->中文名 (\_cfg/Map.bin f1=id,f2=alt_id + STRMap.bin,名称按 f1 优先、f2 回退)
3. char_art/<id名>/ 1625 PNG 角色立绘/头像/半身/卡面 + account_avatars/
   account_frames/ player_photos/ + manifest.json
4. map_art/<id名>/ 34 PNG 地图预览图(preview)+场景图(scene) + manifest.json

## 资源更新

运行脚本 `dump_cfg.py` 后再运行 `extract_all.py`

For Windows

# 版权

美术资源的版权属于<吉星派对>开发团队所有，本仓库仅作美术资源的展示
