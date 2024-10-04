-- 冲榜邪恶 DK ---- 爆发单体 ----- 天灾打击版 -- 全程绿脸
if Prop("宝宝") == 0 then
    Cast("亡者复生")
end
if Prop("战斗中") > 0 and Prop("8 码") > 0 then
    Cast("宠物攻击")
else
    Cast("宠物跟随")
end
-- 召唤石像鬼相关逻辑
if Prop("召唤石像鬼") > 2 or Prop("召唤石像鬼") == 0 then
    if Prop("符文数量") == 0 then
        Cast("符文武器增效")
    end
end
-- 枯萎凋零相关逻辑
if Prop("枯萎凋零") <= 1 then
    if Prop("距离") == 1 then
        Cast("枯萎凋零")
    end
end
if Prop("血之疫病") == 0 then
    Cast("暗影打击")
end
if Prop("冰霜疫病") == 0 then
    Cast("冰冷触摸")
end
-- 进一步的条件判断和操作
if Prop("枯萎凋零") <= 1 then
    if Prop("距离") == 1 then
        Cast("枯萎凋零")
    end
else
    if Prop("魔印") <= 2 and Prop("凋零 dot") >= 4 then
        Cast("天灾打击")
    end
    if Prop("孤寂") <= 1 or Prop("孤寂") <= 3 and Prop("死亡符文数") >= 1 then
        Cast("鲜血打击")
    end
    if Prop("血之疫病") == 0 then
        Cast("暗影打击")
    end
    if Prop("冰霜疫病") == 0 then
        Cast("冰冷触摸")
    end
    -- 召唤石像鬼相关操作
    if Prop("召唤石像鬼") > 59 then
        Cast("手套")
    end
    if Prop("召唤石像鬼") == 0 and Prop("天鬼判定") == 1 then
        if Prop("能量") >= 60 then
            Cast("召唤石像鬼")
            Cast("饰品 1")
            Cast("饰品 2")
            Cast("手套")
            Cast("速度药水")
            Cast("种族技能")
        end
    end
    -- 食尸鬼狂乱和白骨之盾相关操作
    if Prop("食尸鬼狂乱") == 0 and Prop("枯萎凋零") > 4 then
        Cast("食尸鬼狂乱")
    end
    if Prop("白骨之盾") == 0 and Prop("枯萎凋零") > 4 then
        Cast("白骨之盾")
    end
    if Prop("能量") >= 120 then
        Cast("凋零缠绕")
    end
    -- 更多符文相关操作
    if Prop("召唤石像鬼") > 1 then
        if Prop("鲜血符文数") == 2 and Prop("孤寂") > 5 or Prop("鲜血符文数") == 1 and Prop("死亡符文数") == 1 and Prop("孤寂") > 0 or Prop("鲜血符文数") >= 1 and Prop("枯萎凋零") >= 6 and Prop("孤寂") >= 6 then
            if Prop("鲜血符文数") <= 1 and Prop("枯萎凋零") > 10 then
                Cast("活力分流")
            end
            Cast("鲜血打击")
        end
    end
    if Prop("冰霜符文数") == 2 or Prop("冰霜符文数") >= 1 and Prop("枯萎凋零") >= 11 then
        Cast("冰冷触摸")
    end
    if Prop("食尸鬼狂乱") >= 3 then
        if Prop("邪恶符文数") == 2 or Prop("邪恶符文数") >= 1 and Prop("枯萎凋零") >= 11 then
            Cast("暗影打击")
        end
    end
    -- 寒冬号角相关操作
    if Prop("寒冬号角") == 0 and Prop("能量") <= 95 then
        Cast("寒冬号角")
    end
end
if Prop("召唤石像鬼") > 1 then
    Cast("凋零缠绕")
end
Cast("开打")
