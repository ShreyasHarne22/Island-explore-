Island Explore - by Shreyas Harne

TO PUBLISH: upload index.html to any static host (GitHub Pages, Netlify, Vercel, Cloudflare Pages, your own web server).
It is the complete game in one file. It needs internet access to load Three.js from cdnjs.cloudflare.com.

source/ holds the readable parts of the game (optional, for editing).
Rebuild index.html with:
  cat b0_levels.js b_world.js c_props.js c2_ruin.js d_player.js e_audio.js g1_petmodels.js g2_pets.js h1_enemymodels.js h2_combat.js g3_petcombat.js i_neighbors.js f_game.js > all.js
  (cat a_head.html all.js; printf '\n</script>\n') > index.html
