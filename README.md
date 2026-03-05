# SaladDiary
a note about health food
未来添加/修改/删除：只需在 dishes 数组中增删对象，保存后刷新浏览器即可。
版面自动调整：Grid 布局 + height: auto 保证新增后不乱。
打印时只显示正面信息，完整不截断。
在 dishes = [ 数组最后一行（逗号后）复制下面这段模板，粘贴即可：
      {
        id: 16,
        zhName: "新菜名称",
        enName: "New Dish Name",
        desc: "中文描述",
        enDesc: "English description",
        img: "图片链接（推荐Unsplash或Pexels）",
        ingredients: [
          {zh:"食材1", en:"Ingredient1", amt:"100g"},
          {zh:"食材2", en:"Ingredient2", amt:"1个"}
        ],
        calorie: "≈450 kcal",
        steps: [
          "步骤1中文。<br>Step 1 English.",
          "步骤2中文。<br>Step 2 English."
        ]
      }
