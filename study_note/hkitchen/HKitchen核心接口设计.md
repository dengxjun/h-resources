# HKitchen核心接口设计
- v1:一个厨师对应一个厨房，所有操作都由厨师亲自完成
- v2:一个厨房可以容纳多个厨师并行做饭，厨师间共享所有厨房资源
- v3:厨师可以后助理，备菜等步骤可以由助理完成
- v4: 所有食材均计入成本，操作步骤记录时间，操作完成后计算成本
## HeymanKitchen
厨房
- 厨具（Cooker）
- 现有食材（Ingredients）
### Cooker
厨具
- Container（容器，锅碗瓢盆）
- 菜刀（KitchenKnife）
- 灶台（CookingBench）

## Cook
厨师
1. 获取菜谱
2. 检查食材
3. 准备食材
4. 开始做饭
5. 吃饭（非必须）
6. 洗锅（非必须）
## CookMenu
菜谱
- 菜谱名称（menuName）
- 食材元素 (Ingredients)
- 配料元素(Condiment)
- 烹饪步骤(CookProcedure)
## Ingredients
食材
-  蔬菜（Vegetables）
## Condiment
调味品
## CookProcedure
