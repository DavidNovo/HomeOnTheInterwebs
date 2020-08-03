---
title: "Design Challenge_019"
date: 2020-08-02T00:08:50-05:00
draft: false
layout: static/css/design-019.css
---
## Summary (h2 header) {#summary class="pattern-triangles"}

This is an experiment using CSS to make simple patterns using gradients.

Patterns I am making:

1. Triangles
2. Stripes
3. Dots
4. Grid

Here is the bit of CSS that I used:
{{< highlight css>}}
 /* Making patterns using CSS gradients */
  /* I want to make these patterns: triangles, stripes, dots, and a grid. */

  /* Using angles, 0deg creates vertical gradient running from bottom to top, 90deg is horizontal 
  gradient running from left to right.  This gradient used a hard stop for the colors, 50% through the gradient.
  These gradients are not repeating.
  */
  .pattern-triangles {
    background-image: linear-gradient(45deg, currentColor 50%, transparent 50%);
    background-size: 25px 25px;
  }

  /* This pattern is using the em for size, not px. */
  .pattern-stripes-horizontal {
    background-image: linear-gradient(0deg, transparent 50%, currentColor 50%);
    background-size: 0.1em 0.1em;
  }

  /* As with linear gradients, all you need to create a radial gradient are two colors. 
  By default, the center of the gradient is at the 50% 50% mark, and the gradient is 
  elliptical matching the aspect ratio of it's box.  In this case the box is square, so the aspect
  ratio of the box is 1:1 */
  .pattern-dots {
    background-image: radial-gradient(currentColor 1px, transparent 1px);
    background-size: calc(10 * 1px) calc(10 * 1px);
  }

  /* Gradients can be overlayed.  The first gradent defined is the one applied on top.
  By default, gradients run from top to bottom (I am not using angles for this gradient).
  The direction of the gradient can be changed using clauses like 'to right'*/
  p,
  .pattern-grid {
    background-image: linear-gradient(currentColor 1px, transparent 1px),
      linear-gradient(to right, currentColor 1px, transparent 1px);
    background-size: 1em 1em;
  }
{{</ highlight >}}
***

## O penates includit sunt Graias contemptus rigidoque (h2 header) {class="pattern-stripes-horizontal"}

Tasks

- [x] Bacon ipsum dolor amet shank
- [ ] Pig prosciutto
- [ ] Flank ground round
  
First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: Tollite at plenas locumque.

Bacon ipsum dolor amet brisket buffalo flank salami landjaeger ribeye sirloin pastrami turducken. Biltong swine meatloaf prosciutto. Sirloin ground round tongue, bresaola short loin cow leberkas. Filet mignon swine chicken pig shankle jerky jowl ham hock buffalo beef pancetta. Meatball swine spare ribs bresaola, tenderloin bacon chicken burgdoggen sausage frankfurter shoulder. Porchetta kevin pig fatback jowl, brisket capicola tenderloin meatloaf venison hamburger.

## Postes cum placui (h2 header) {#header-id-h2 class="header2 pattern-dots "}

Lorem markdownum vultus *verba bracchia italic* removerat opem morboque oculisque
clausit. Phrygii Eueninae, illum animo, et **nulla possederat boldat** de umbras, sub?
Est [o imo adfatur](http://ense.net/patiensque-conclamat.html) ut medicamina
Maenalon, stipite terris pigneror petis violaverat fixum.

### Est te fit (h3 header class="subheader")

Si inpulsu offensa sororis vimque sub Pharonque dicunt confesso quid, intravit!
Nec fronte Veneris nostros Charybdis tibia, eventusque latebris pacis, defecto
tantusque ungues increpuit! Est columba, circumtulit domo languentique Vesta
pectusque: est: [habeto tenet](http://www.caerulaque-iphide.com/iterumque.html)
illa. Quaeratur negat tenens portabat, flectitur videam ima Latinus auro loquor
[planxerunt](http://qui.net/lolium.aspx) inter, victoria [nam
Diana](http://sic.io/vix-est). Fuerant pudet nexus culpae procul adnuit
ingemuitque nullo longaque postquam.

Hospes se iuvenca Hactenus dumque decet alta, brevissimus rosarum veros fluere
taurum Nox, est. Adhuc fronte Lyciae fallunt! Dixit in aliae finire putria
guttae germana Scorpius adventu praemonuisse illic guttis excussit si onus.
Causa foret sensisse [et](http://quae.io/idque.html) letique citus, invide alite
tempora munere, **struxisse bolde**, se.

## Senecta erat mihi quaque lumina (h2 header) {class="header2 pattern-dots"}

Lorem markdownum protinus restabat de parte probatum Troiae ira attonitas aut
vates vulneris referuntur sanet. Tumidi ex validi currus patria sponte poscenti
rostrisque, vina ante, et heros concavat Ismenides cremantur satis dextra; dum.
Vicina suspiria.

Ball tip strip steak pork prosciutto, brisket turkey kevin alcatra t-bone meatloaf ribeye jerky beef filet mignon. Shank pork landjaeger sirloin, ham tongue turkey pork loin. Buffalo tenderloin shankle leberkas ground round, burgdoggen andouille kielbasa sausage ham hock brisket. Pancetta prosciutto cow short loin bacon salami. Landjaeger frankfurter short loin flank jerky tri-tip pancetta kielbasa swine short ribs beef sirloin pork loin. Flank pastrami chislic, short ribs doner turducken t-bone corned beef swine sausage cupim beef pig tail kevin.

Mihi visa cineri totiens. Properabat matris Xanthique proxima pictas
[aversa](http://europenramos.org/dilexit.html), mirere vinci, iterum orant,
movet alterius. Cribri Invidiam his.

    intellectual.macro_topology = copyrightMyspaceBoot;
    switch_spoofing(windowsUps);
    if (ppp_crm(clean_java_interpreter - 43 - 2, fragmentation_interface_bus +
            device, nativeSurface(enterprise, operationAlertGraphic + drm, cable
            + 2))) {
        wpa *= simplexAdsl(spoofing, integrated_terminal_lifo(index,
                troubleshooting, cleanCode));
        search_cpu_drive = character;
    }
    var documentScraping = keyboard;

Aestibus vitae, mihi, Iolen suscipiunt **aqua bolda**, aeno novo ullus et veluti,
timoris videre, magna, eburno. Comas excussit amare pluvialibus solus tracto
formicas filius.

- Tota manus narrare ubi voce
- Fessa inde huius in etiamnum
- O conscia constitit tum
- Coeamus iudicium
- Regem fuit fecundaque
- Nos respicere

## Auditum visa (h2 header) {class="header2 pattern-dots"}

Ad adacto oscula. Post pomaria dolebat latura quod! Opus venit validisne non
[cur](http://hocparens.net/) introrsus crescere hasta! Pecudes ossa ut duce
*mutabitur galeae itlaiciani*, denique a monstri annum fautrix! Qui feroxque praeter.

    if (mysql / keylogger_ddl_macintosh - adapter >= dfs_pci_card(
            hitComputer.brouter_newline(494822, party, scareware), cut,
            monitor_market_extranet + jquery)) {
        latency_mail += netbiosInternetUser;
        leopard_megabyte.wired_boolean = 3;
        hertz.wirelessAvatarSeo = edutainment_serial_reader;
    }
    var click_tag = flashMatrix(41 + digitizeMasterNic + itDrivePpga);
    nameJumper.compiler_mount.snapshot_point(editorDisk, dual_data_log.capacity(
            newsgroupPretest), development_page_host);

Possis regia, disiectum annis petit confundere primi pugnantem mota: Argo corpus
petita. Sibi Oedipodioniae iussus in utque premit nomen sanguine. Clarum illi
portas hic emisitque! *Nec teneri italiciani* mentita, quamvis modo miserantibus Iphis ac
ligo, maledicere, fecit, pete heres collecti in.

- Vagus sagittis nec iungi relinquit
- Suae neque Lucinam procerum talibus nec aether
- Exire nocte cernere

## Fugacibus aethere gloria (h2 header)

Quoque aquarum querellis Iove nomen **cupio boldo** spectansque neque, nec quae aliae.
Pulsant Cyllenius terrificam ad collem secum ora disque; aversum, per illis
addit.

### Prunaque et teque. (h3 header)

Sed ubi movetur superum quis Thestiadae parte: gradu et
[ventos](http://www.collum.com/) quoque inque, is. Meritumque iamque sacerdos,
et aspicis, dedit, exitio in bene, genus medio cum bello mihi
[volucres](http://videtmedii.net/vertere.php), factum. Et nam si ipsaque
effugimus, stat errat sensit ignis Paean, nec, illa mihi una acta superest
venerit.

    twain_target_dma(keystrokePythonParty, leopardLdapCommand + map_system(
            address, srgb_sip, ppmLion), internal(data, registryMetaRss, raw));
    var scroll = scanCcPpm;
    ipx -= 4;

#### Hippotades (h4 header)

Hippotades capit inde sive viri manus declivis, sagitta
[continuam](http://minos-tu.io/amnis). Mugitus me Nessus ad Acasto fors, est
quod natant. Ignibus dignissima facinus cura cruentat pervidet viros materia
Picus! Quam sui me tumulus et **Siculo putes mirabilis** et infra! Quam exta
demersit crimine nequiquam structis ponto, os ferarum, Agamemnona, sumitque.

1. Et idem in dedit popularis at alvum
2. Cupidine maligne humum congrediturque longis est vulnus
3. Tritis Scylla ad parva blandita irascitur obstipuit
4. Nulli latuitque
5. Utinamque quod perfudit iam
6. Continuam suarum ferox

##### Ademdum (h5 header)

Nobis primordia stagna falleret pondere flentemque obstaret, et seducunt funda
et. Causa ac quod, quas habet [illo](http://cadet.org/) perdiderat squamis Iove
tempore est. Pariterque ficti. Laniger extemplo in, humo positaeque illa, et ut
quoque facie medios exstinctus tantosque aura radiabant
[vive](http://www.carendum.io/).
