# CBOW Results 
Trained CBOW model from scratch on Shakespeare Plays. Th results show loss and 10 common words associated with their closest context words according to the model. 
![image](https://github.com/user-attachments/assets/abb10474-fb1c-41f7-96ef-f96a3096902f)

```
Closest words to 'thy': ['his', 'my', 'your', 'henry’s', 'cuckoobuds', 'hotspur’s', 'england’s', 'her', '’faith', 'lawrence’']
Closest words to 'woman': ['maid', 'hen', 'transformation', 'caesar—', 'caitiff', 'treasonous', 'abortive', 'daniel', 'pit', 'creature']
Closest words to 'caesar': ['antony', 'enobarbus', 'cleopatra', 'brutus', 'agrippa', 'cicero', 'lucius', 'agamemnon', 'gentle—', 'banquo']
Closest words to 'hamlet': ['polonius', 'porter', 'laertes', 'guildenstern', 'stephano', 'horatio', 'question', 'purpose”', 'fly—', 'cassio']
Closest words to 'king': ['cozen’d', 'bishop', 'king”', 'warmth', 'prologue', 'crabbed', 'unqueened', 'imprisonment', 'warthoughts', 'crutch']
Closest words to 'love': ['julia', 'dream', 'palate', 'unpartial', 'sake', 'abominations', 'envy', 'eyesight', 'briers', 'childhood']
Closest words to 'god': ['councilchamber', 'implies', 'stink', 'jesu', 'fallingfrom', 'powers', 'heavens', 'heaven', 'safety', 'herod']
Closest words to 'lady': ['wife', 'case', 'hecate', 'niece', 'steed', 'gallery', 'things—', 'rumour', 'boy', 'muse']
Closest words to 'death': ['presentment', 'extremest', 'posterity', 'objections', 'bandit', 'timeless', 'stores', 'counsels', 'destruction', 'womb']
Closest words to 'prince': ['cuckold’s', 'befall', 'merciless', 'saidst', 'worcester', 'outgoes', '“ever”', 'king”', 'aesculapius', 'king']
Closest words to 'pray': ['beseech', 'will', 'prithee', 'thank', 'befriend', 'grant', 'conjure', 'berhyme', 'accost', 'fray’d']
```

# Hidden Markov Model Results 
In this training project, I used Hidden Markov Models architecture coded from scratch to generate new Shakespeare Sonnets based on training on a collection of Shakespearean Sonnets. HMM (a generative model) results comparison with LSTM is also shown below in the results. 



![image](https://github.com/user-attachments/assets/d00d1574-2cc1-4bfb-b7c3-c51217d03d53)

### Word Clouds 
<img width="1127" alt="image" src="https://github.com/user-attachments/assets/09ecadff-3960-42a0-a547-fbffbc7feb68" />

```
n_state= 3
Sonnet: 
the thou love make deceive be where you refigured
and it would but is me should absent of
a frown'st receiv'st dead desert live of thrall
issue summer's of with than oft orphans
eye's always is alters that put seem third
and scope on of womb such grew that love up
of dear not whether sweet pride bearing expiate
to best tyrants saw in corrupting mortal
full crowned oaths another fled spacious
your worst allow reap my not as fire merit
interim the my to for though but jewel thou
such new fair you from with tongues have to kindness
thy the of which every need yet an drugs
then hold my good wrongfully we i so

Rhyme scheme: abcdefghijklmn


n_state= 7
Sonnet: 
therefore that never long better and will
wrought public am i within been i not
self-loving against sweet alteration
for the contains do my overturn to
my slept of years sounds passed of make a i
a respect my rud'st thou beauty on the
or with thee fair reserve my very of
false not whose the pyramids before his
uncertain buds thy robbery in great mayst
flowers compare of behind eyes th' yet with alt'ring
rebel not ocean as eye look in this
mistress to days takes as it thou sigh some
eloquence with it you tyranny give
thy keen thou that that who from mayst yet a

Rhyme scheme: abcdefghijhklm

n_state= 9
Sonnet: 
thanks suspect seasons' loving cannot as with
yet not always is winter comments his
imperfect thee action methods a effect
part and falsehood is should unthrifts intermixed' show
of you so of not hand a kill alone
seem not razed then but old my muse with slay
love's skill never upon my black miles wealth
praise of clean delights to by too sake lip
from lengths fair by mournful and end rage youth
without all now men's morn and each is gold
thou must to for thou beauteous glory thy
so of hugely worst drops why what i their
gored thy sun of winter's eyes most your age
creatures so i love enjoyer woe to

Number of lines: 14

Rhyme scheme: abcdefagahijkl
n_state= 11
Sonnet: 
tears thou in of choirs an were your pleasures
are i you call in my self against our
appetite have not good eyes for nothing thou
i thine own world's smell of proud hand am i
am that not storm-beaten thing be the parts
not you show me shadow of truth mine beated
me with self shall be hooks trim but to progress
giving do it eve's external o'erpressed
away came shines year women's and place no
mow and even lies my thee most to hour thee
birth his them so more by worth common which
threescore delight there his thing to mine whose
lion's me yet a dateless stand esteemed
me can worms to her prize doth that bed-vow

Rhyme scheme: abcdefgfhijkfl

n_state= 13
Sonnet: 
thee thee one of dear are vial wrackful
prize all name words breath my my proved alack
oft am bear past curse feeds keeps obsequious
they inviting thou never yet shames not
not i age in a remain sepulchres
praise this eyes receiv'st nor nothing wilt so
i that old tillage on dead of wait souls
should be eye thy bright too other his deface
live from deserved night an fierce remembrance
youth your a one mine nature's as fashion my
leave that love's those every thou bold for thy
set me but with ill world's to for time light
this thou none welcome hand my write all delves
the fuel large but with truth hath the dumb more


Rhyme scheme: abcdefghhijkel
n_state= 15
Sonnet: 
then thou minion in doth basest whose yet
odour a idol with despite loss is
thy advocate many a end old but contented
joy look their married receives that without
self that nymphs it aid i am repose the
plight to and rehearse not like writ shade hear
the in when record do live what seek of
and defence thought doth up possession dissuade
gilded my find can mounted be her scarlet
yours with a pour'st my pain and i my hour
thy made to fast thoughts do love thoughts strongly
justify hearts womb high within these in
times huswife thy steal that whom for party
you all false sit height my for world thou latch
```


## Example LSTM Generated Sonnets 
```

Generated Text (Temperature = 1.5):
 shall i compare thee to a summer's day?
nour remove,
to may too,
me frught,ing toy,
i self infall-com'stannees despair injurious distainless life thou to me within be:
let my lay chast in one of say infecrieg,
a is it not did exchese:
so fron.
for from date:
  i being dombid mine,
rhy our most to uge,
when other in you art,
to wantanchoods which alters when it fil'st be by spirit in one, sip why wish a bate thy cure,
thy mind must graces, carting sing:
  in my love for summer since j

Generated Text (Temperature = 0.75):
 shall i compare thee to a summer's day,
when i all others worse alone.


                     
that thou dost lives my desire doth with lossess on your sight,
by thy parted with all my name refeit.
so art to the time do i ten with my love stol'n i do boundly pening,
and nature basome hath in my poor from when they 'tis long of your love,
to make me to god.
my that i must mild me, some vanicled,
that love in love to thee,
yet what distill delight:
so all my worth and werk in this dail

Generated Text (Temperature = 0.25):
 shall i compare thee to a summer's day,
when i say thy beauty of thy self thee to me than thou art make me fair,
the old are dead woods,
and that in my thoughts (from love's fresh of my sake again, and therein shame do i in my self in love to set me with mine,
and therefore to be dearths of self-love thee more,
the right be error and hours that wear these particulages of this man on dead and world of the sun in heavenly glade,
to shall summer's rage show me thee to the motion of thin
```



