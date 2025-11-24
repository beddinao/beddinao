<!--# Hi I'm Bilal Eddinaoui

### Student at <a href="">*`1337`* </a>, the <a href="">*`42`*</a> Network, khouribga Campus 
-->

```assembly
//; KickAss 6502 Assembler
.pc = $0801 "Basic Upstart"
:BasicUpstart(start)

.pc = $0810 "About Me"

.encoding "screencode_upper"
text:
    .text "                                        "
    .text "            BILAL EDDINAOUI             "
    .text "                                        " 
    .text "           SYSTEMS ARCHITECT            " 
    .text "                                        "
    .text "      C/C++ | TCP/IP | AGENTIC AI       "
    .text "                                        "
    .byte $00

start:
    lda #$00
    sta $d020
    sta $d021
    ldx #$00
    
print:
    lda text,x
    beq loop
    sta $0400,x
    lda #$01
    sta $d800,x
    inx
    bne print
    
loop:
    jmp loop

/*  
    . can be run online on my emulator: https://c64.beddinao.me
    . or on: https://ide.retrogamecoders.com/?platform=c64
    .prg binary file: https://c64.beddinao.me/programs/About_Me.prg
*/
```

<div align="center" width="100%">
  <a href="https://github.com/beddinao">
    <img src="https://custom-readme-stats.vercel.app/api/top-langs/?username=beddinao&cache_seconds=21600&theme=dark&border_radius=16&bg_color=1e252b&text_color=bfbfbf&show_icons=true&icon_color=ff8070&hide_border=true&count_weight=0.5&title_color=dbdbdb&hide=Objective-C,CMake,Perl,Java&stats_format=bytes" align="center" width="37%" />
  </a>
  <a hreef="https://github.com/beddinao"">
    <img src="https://custom-readme-stats.vercel.app/api?username=beddinao&theme=dark&bg_color=1e252b&text_color=bfbfbf&border_radius=16&show_icons=true&icon_color=ff8070&ring_color=c4e3ff&hide_border=true&line_height=30&show=prs_merged,prs_merged_percentage&custom_title=General%20Stats&title_color=dbdbdb" align="center" width="58%" />
  </a>
</div>

<br>

<!--div align="center" style="width: 100%">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=beddinao&theme=xcode&color=bfbfbf&hide_border=true&days=40&bg_color=1e252b&area=true&radius=16&custom_title=Contributions%20graph%20in%20the%20last%2040%20days&title_color=dbdbdb&height=600" style="width: 100%" align="center" />
</div-->

  <!--p align="left"> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/> </a> <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> </p-->

<!--div width="100%" align="start" >
  <img src="./42-stats-badge.svg" alt="42-stats-badge"  />
</div-->

<!--div align="right"> <img src="https://komarev.com/ghpvc/?username=beddinao&label=Profile%20views&color=c7c7cc&style=flat-square" alt="beddinao" /> </div-->
