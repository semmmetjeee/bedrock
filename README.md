# BedrockMenuBridge

Een Paper-plugin voor Geyser en Floodgate. Virtuele plugin-menu's, waaronder DeluxeMenus, worden voor Bedrock-spelers als native Bedrock Forms geopend.

- Elk huidig slot wordt automatisch een knop met naam en lore.
- Minecraft-items worden naar Bedrock-textures omgezet: DIAMOND gebruikt textures/items/diamond.
- Een gekozen knop voert de bijbehorende Bukkit left-click uit; DeluxeMenus houdt dus zijn eigen commands, requirements en permissions.

Vereist: Paper 1.21.4+, Geyser en Floodgate op dezelfde backend-server.

Bouw lokaal met mvn clean package. De JAR komt in target/BedrockMenuBridge.jar.
