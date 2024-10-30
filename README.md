# ItemBuilder
Create advanced ItemStacks with just one line of code.  
  
### Standart ItemBuilder API Usage
1. Create a Instance of the ItemBuilder: `ItemBuilder builder = new ItemBuilder(Material.GLOWSTONE);`  
2. Modify the ItemStack using one of the many methods, for example: `builder.displayname("§6ItemBuiler Glowstone");`  
3. When you are finish modifing it, use `builder.build();` to get the Bukkit ItemStack back  
You can also do all steps in just one line: `ItemStack item = new ItemBuilder(Material.GLOWSTONE).displayname("§6ItemBuilder Glowstone").build();`  
