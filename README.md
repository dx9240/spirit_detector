# spirit_detector "Psychic Learn"

Link to the demo: https://lesia-tkacz.app.n8n.cloud/webhook/63ad13d4-691b-47f3-b146-d1701935cad0/chat
demo video: https://www.loom.com/share/3ecb11ebc8c54dab8dc716d47e67e966?sid=d36565de-dc22-46fc-b0e4-dee7fcdf539a

Usage: Upload a photo of an object and type "analyze" into the chat before submitting. User can ask questions about the resulting spectral analysis data.

This is a a creative aid for players of narrative roleplaying games. This fits well with collaborative storytelling tabletop roleplaying games which have supernatural themes, such as Urban Shadows.
 It can also be used to supplment the activity of thrifting, antiquing, and flea market browsing as a storytelling activity. Pyschic Learn is to be used as a spectral analysis device, or, ghost hunting device that scans objects for supernatural connections and resonaces. It therefore allows the user/player to interact with the real world by selecting physical objects to feed into the Psychic Learn device, and augmenting this (creative) choice with the power of a LLM agent. Here, then, the unpredictability and surprisal which can be charactsitic of LLM output is leveraged as a creative aid. 
Inspired by ARGs (alternate reality games), the book 'Ghost Hunting for Dummies', commerical 'ghost hunting' devices, the board games Mysterium and Dixit, interactive fiction and locative narratives,and tabletop roleplaying games such as Urban Shadows.

Pyschic Learn helps the creative burden problem that roleplaying game dungeon masters and masters of ceremony have with constantly needing to come up with new narrative senarios and narrative 'hooks' to engage players and encorage interaction.

I used n8n workflow automation to build the Mistral agent using Pixtrel large and the wikipedia search tool. By including references to information on wikipedia, the user will have the opporunity to leave the Psychic Learn interface and research the information produced by it on another platfrom (such as web search), thereby supporting a more immersive ARG style of play.

NOTES and future TODO:

Create object reading agent
 - How could this adapt to the environment? (location, temperature, local landmarks, current date)
 - Implement a psuedo-code style interaction for a more immersive 'device-y' feel
 - Refine the 3 types of supernatural data that the device outputs


 Create psychic vision agent
 - Based on a combination of the user's input and generated spirit data, generate a psychic vision 'card' as a final product/collectable for the user to have as a momento and potentially use as part of roleplaying game prompting.


Extended Play
 - Make it possible to input multiple object photos to relate to the same reading
 - Create a folio/grimorie 'scrap book' to collect the narrative vingette produced by the spirit reading and psychic vision card. Allow to user to write in their own feild notes as the investigator.
