xmldir = $(pkgdatadir)/@PACKAGE_DATA_DIR@/lang

xml_in_files = \
	words.xml.in

xml_DATA = $(xml_in_files:.xml.in=.xml)

#
# Do not use the INTLTOOL_XML_RULE, we don't need to embed the translations
# in the file themselves. GCompris pick the translations from the po file at
# runtime.
#
$(xml_DATA): %.xml: %.xml.in
	sed -e "s/\(<\{1\}\/*\)_/\1/g" $< > $@


imgdir = $(pkgdatadir)/@PACKAGE_DATA_DIR@/lang
img_DATA = \
	button_front.svg \
	background.svgz \
	repeat.svg

wordsimgdir = $(pkgdatadir)/@PACKAGE_DATA_DIR@/lang/words
wordsimg_DATA = \
	words/README \
	words/accountant.png \
	words/ache.png \
	words/acorn.png \
	words/actor.png \
	words/air_horn.png \
	words/alarmclock.png \
	words/alligator.png \
	words/alphabet.png \
	words/anchor.png \
	words/angel.png \
	words/angry.png \
	words/animal.png \
	words/ankle.png \
	words/ant.png \
	words/anteater.png \
	words/antelope.png \
	words/apple.png \
	words/apple_tree.png \
	words/appliance.png \
	words/apricot.png \
	words/arm.png \
	words/armchair.png \
	words/artichoke.png \
	words/artist.png \
	words/asparagus.png \
	words/astronaut.png \
	words/ate.png \
	words/athlete.png \
	words/avocado.png \
	words/ax.png \
	words/baby_bottle.png \
	words/back.png \
	words/badge.png \
	words/bag.png \
	words/bait.png \
	words/bake.png \
	words/balance.png \
	words/bald.png \
	words/ball.png \
	words/ball_of_yarn.png \
	words/ball_soccer.png \
	words/ballet.png \
	words/bank.png \
	words/banker_female.png \
	words/bark.png \
	words/barn.png \
	words/bat.png \
	words/bath.png \
	words/bathing_suit.png \
	words/bay.png \
	words/beach.png \
	words/bead.png \
	words/bean.png \
	words/bear.png \
	words/beard.png \
	words/beat.png \
	words/beaver.png \
	words/bed.png \
	words/bedroom.png \
	words/bee.png \
	words/beef.png \
	words/beetle.png \
	words/beg.png \
	words/behind.png \
	words/bell.png \
	words/belly.png \
	words/bench.png \
	words/bib.png \
	words/big.png \
	words/big_top.png \
	words/bike.png \
	words/bird.png \
	words/bit.png \
	words/bite.png \
	words/black.png \
	words/blackberry.png \
	words/blackbird.png \
	words/blade.png \
	words/blind.png \
	words/blink.png \
	words/block.png \
	words/blond.png \
	words/blue.png \
	words/blueberry.png \
	words/blush.png \
	words/board.png \
	words/boat.png \
	words/boil.png \
	words/bolt.png \
	words/bomb.png \
	words/bone.png \
	words/book.png \
	words/bookcase.png \
	words/bottom.png \
	words/box.png \
	words/boxer.png \
	words/boy.png \
	words/braid.png \
	words/brain.png \
	words/branch.png \
	words/bread.png \
	words/break.png \
	words/breast.png \
	words/brick.png \
	words/bricklayer.png \
	words/bride.png \
	words/bridge.png \
	words/bright.png \
	words/broccoli.png \
	words/brother.png \
	words/brown.png \
	words/brush.png \
	words/bubble.png \
	words/bucket.png \
	words/bud.png \
	words/buffalo.png \
	words/bug.png \
	words/bulb.png \
	words/bull.png \
	words/bump.png \
	words/bun.png \
	words/bus.png \
	words/bush.png \
	words/butcher.png \
	words/butter.png \
	words/butterfly.png \
	words/button.png \
	words/cabbage.png \
	words/cabin.png \
	words/cacao.png \
	words/cactus.png \
	words/cage.png \
	words/cake.png \
	words/call.png \
	words/camel.png \
	words/camera.png \
	words/camp.png \
	words/can.png \
	words/canary.png \
	words/candle.png \
	words/candy.png \
	words/cane.png \
	words/canoe.png \
	words/canon.png \
	words/canyon.png \
	words/cap.png \
	words/cape.png \
	words/car.png \
	words/carafe.png \
	words/card.png \
	words/carnival.png \
	words/carpenter.png \
	words/carpet.png \
	words/carrot.png \
	words/cart.png \
	words/cash.png \
	words/castle.png \
	words/cat.png \
	words/cat_female.png \
	words/catch.png \
	words/caterpillar.png \
	words/cauldron.png \
	words/cauliflower.png \
	words/cave.png \
	words/cavern.png \
	words/celery.png \
	words/centipede.png \
	words/cereal.png \
	words/chain.png \
	words/chair.png \
	words/chalk.png \
	words/chameleon.png \
	words/chandelier.png \
	words/chat.png \
	words/cheek.png \
	words/cheer.png \
	words/cheese.png \
	words/chef.png \
	words/cherry.png \
	words/chest.png \
	words/chick.png \
	words/chicken.png \
	words/chief.png \
	words/child.png \
	words/chimney.png \
	words/chimp.png \
	words/chin.png \
	words/chocolate.png \
	words/chop.png \
	words/chores.png \
	words/christmas.png \
	words/cigar.png \
	words/circus.png \
	words/city.png \
	words/clam.png \
	words/clap.png \
	words/class.png \
	words/claw.png \
	words/clay.png \
	words/clean.png \
	words/cleaning_lady.png \
	words/cliff.png \
	words/climb.png \
	words/clock.png \
	words/cloth.png \
	words/clothes_hanger.png \
	words/cloud.png \
	words/cloudy.png \
	words/clover.png \
	words/clown.png \
	words/coach.png \
	words/coast.png \
	words/coat.png \
	words/cobra.png \
	words/coconut.png \
	words/cod.png \
	words/coffee.png \
	words/coin.png \
	words/cold.png \
	words/color.png \
	words/colt.png \
	words/comb.png \
	words/cone.png \
	words/cookie.png \
	words/cork.png \
	words/corn.png \
	words/couch.png \
	words/cough.png \
	words/couple.png \
	words/cow.png \
	words/cowboy.png \
	words/crab.png \
	words/cradle.png \
	words/craft.png \
	words/crawl.png \
	words/crazy.png \
	words/creek.png \
	words/crepe.png \
	words/crib.png \
	words/criminal.png \
	words/croak.png \
	words/crocodile.png \
	words/cross.png \
	words/crow.png \
	words/crown.png \
	words/crumb.png \
	words/crust.png \
	words/cry.png \
	words/crystal.png \
	words/cube.png \
	words/cucumber.png \
	words/curtain.png \
	words/cut.png \
	words/cute.png \
	words/dad.png \
	words/daffodil.png \
	words/daisy.png \
	words/dam.png \
	words/dance.png \
	words/dandelion.png \
	words/danger.png \
	words/dark.png \
	words/dart_board.png \
	words/date_fruit.png \
	words/deer.png \
	words/den.png \
	words/desert.png \
	words/desk.png \
	words/dessert.png \
	words/diamond.png \
	words/dig.png \
	words/dirt.png \
	words/dirty.png \
	words/dish.png \
	words/dishcloth.png \
	words/dive.png \
	words/doctor.png \
	words/doe.png \
	words/dog.png \
	words/doll.png \
	words/dolphin.png \
	words/domino.png \
	words/door.png \
	words/doormat.png \
	words/dot.png \
	words/doughnut.png \
	words/dove.png \
	words/dragon.png \
	words/dragonfly.png \
	words/drank.png \
	words/draw.png \
	words/drawer.png \
	words/dream.png \
	words/dress.png \
	words/drink.png \
	words/drinking.png \
	words/drip.png \
	words/drive.png \
	words/drool.png \
	words/drum.png \
	words/dry.png \
	words/duck.png \
	words/duck_mother.png \
	words/dune.png \
	words/dwarf.png \
	words/eagle.png \
	words/ear.png \
	words/earth.png \
	words/eat.png \
	words/egg.png \
	words/eggplant.png \
	words/eight.png \
	words/elbow.png \
	words/electrician.png \
	words/eleven.png \
	words/elk.png \
	words/empty.png \
	words/engine.png \
	words/engineer.png \
	words/eraser.png \
	words/explore.png \
	words/eyelash.png \
	words/eyes.png \
	words/face.png \
	words/fair.png \
	words/fairy.png \
	words/fall_down.png \
	words/fall_season.png \
	words/family.png \
	words/fan.png \
	words/farm.png \
	words/farmer.png \
	words/fat.png \
	words/faucet.png \
	words/fawn.png \
	words/feast.png \
	words/feather.png \
	words/feed.png \
	words/feet.png \
	words/fell.png \
	words/femur.png \
	words/fetch.png \
	words/fig.png \
	words/fin.png \
	words/find.png \
	words/finger.png \
	words/fire.png \
	words/fire_extinguisher.png \
	words/fireman.png \
	words/fish.png \
	words/fisherman.png \
	words/fist.png \
	words/five.png \
	words/flacon.png \
	words/flag.png \
	words/flame.png \
	words/flamingo.png \
	words/flash.png \
	words/flat.png \
	words/flies.png \
	words/flight.png \
	words/float.png \
	words/flour.png \
	words/flower.png \
	words/fluff.png \
	words/flute.png \
	words/fly.png \
	words/foam.png \
	words/food.png \
	words/foot.png \
	words/forest.png \
	words/fork.png \
	words/fountain.png \
	words/four.png \
	words/fox.png \
	words/freeze.png \
	words/friend.png \
	words/fries.png \
	words/frog.png \
	words/front.png \
	words/frown.png \
	words/fruit.png \
	words/fudge.png \
	words/full.png \
	words/fun.png \
	words/fur.png \
	words/game.png \
	words/garage.png \
	words/garden.png \
	words/garlic.png \
	words/gem.png \
	words/giant.png \
	words/gift.png \
	words/giraffe.png \
	words/girl.png \
	words/glass.png \
	words/glasses.png \
	words/glove.png \
	words/glue.png \
	words/gnome.png \
	words/goat.png \
	words/golden.png \
	words/golf.png \
	words/goose.png \
	words/gorilla.png \
	words/grain.png \
	words/grandmother.png \
	words/grape.png \
	words/grapefruit.png \
	words/grass.png \
	words/grave.png \
	words/gray.png \
	words/green.png \
	words/grill.png \
	words/grin.png \
	words/ground.png \
	words/growl.png \
	words/guignol.png \
	words/guinea_pig.png \
	words/gum.png \
	words/hair.png \
	words/hair_dryer.png \
	words/half.png \
	words/ham.png \
	words/hammer.png \
	words/hand.png \
	words/handlebar.png \
	words/happy.png \
	words/harp.png \
	words/hat.png \
	words/hatch.png \
	words/hay.png \
	words/head.png \
	words/hear.png \
	words/heat.png \
	words/hedge.png \
	words/hedgehog.png \
	words/heel.png \
	words/helmet.png \
	words/hen.png \
	words/herd.png \
	words/high.png \
	words/hike.png \
	words/hill.png \
	words/hip.png \
	words/hippopotamus.png \
	words/hit.png \
	words/hive.png \
	words/hockey.png \
	words/hole.png \
	words/home.png \
	words/hook.png \
	words/hop.png \
	words/horse.png \
	words/hose.png \
	words/hospital.png \
	words/hot.png \
	words/hot_dog.png \
	words/hound.png \
	words/house.png \
	words/howl.png \
	words/hug.png \
	words/huge.png \
	words/hummingbird.png \
	words/hunchback.png \
	words/hunter.png \
	words/husband.png \
	words/hut.png \
	words/hyena.png \
	words/ice.png \
	words/iceberg.png \
	words/iguana.png \
	words/ill.png \
	words/ink.png \
	words/island.png \
	words/jacket.png \
	words/jaguar.png \
	words/jam.png \
	words/jay.png \
	words/jelly.png \
	words/jellyfish.png \
	words/jewel.png \
	words/job.png \
	words/jockey.png \
	words/jog.png \
	words/judge.png \
	words/judo.png \
	words/juggler.png \
	words/juice.png \
	words/jump.png \
	words/kangaroo.png \
	words/keel.png \
	words/kernel.png \
	words/keyboard.png \
	words/kimono.png \
	words/king.png \
	words/kiss.png \
	words/kitchen.png \
	words/kite.png \
	words/kitten.png \
	words/kiwi.png \
	words/knee.png \
	words/kneel.png \
	words/knife.png \
	words/knight.png \
	words/knit.png \
	words/knot.png \
	words/koala.png \
	words/lad.png \
	words/lady.png \
	words/ladybug.png \
	words/lake.png \
	words/lama.png \
	words/lamb.png \
	words/lamp.png \
	words/land.png \
	words/lane.png \
	words/lap.png \
	words/lasso.png \
	words/laugh.png \
	words/lava.png \
	words/lawn.png \
	words/lawyer.png \
	words/leaf.png \
	words/ledge.png \
	words/leek.png \
	words/left.png \
	words/leg.png \
	words/leg_animal.png \
	words/lemon.png \
	words/lemonade.png \
	words/lemur.png \
	words/leopard.png \
	words/lettuce.png \
	words/librarian.png \
	words/lick.png \
	words/lid.png \
	words/lift.png \
	words/light.png \
	words/lighthouse.png \
	words/lightning.png \
	words/lilac.png \
	words/lime.png \
	words/line.png \
	words/link.png \
	words/lion.png \
	words/lion_cub.png \
	words/lip.png \
	words/liquid.png \
	words/lizard.png \
	words/lobster.png \
	words/log.png \
	words/look.png \
	words/lunch.png \
	words/mad.png \
	words/magic.png \
	words/magnet.png \
	words/magnifying_glass.png \
	words/magpie.png \
	words/mail.png \
	words/man.png \
	words/mane.png \
	words/mango.png \
	words/map.png \
	words/maple.png \
	words/marble.png \
	words/mashed_potatoes.png \
	words/mask.png \
	words/mast.png \
	words/mat.png \
	words/match.png \
	words/mate.png \
	words/mattress.png \
	words/mauve.png \
	words/meal.png \
	words/meat.png \
	words/mechanic.png \
	words/medal.png \
	words/meet.png \
	words/melon.png \
	words/men.png \
	words/merry-go-round.png \
	words/mice.png \
	words/microphone.png \
	words/milk.png \
	words/mill.png \
	words/mimosa.png \
	words/mirror.png \
	words/mixer.png \
	words/mole.png \
	words/mom.png \
	words/moon.png \
	words/moose.png \
	words/mop.png \
	words/mosque.png \
	words/mosquito.png \
	words/mother.png \
	words/motorcycle.png \
	words/mountain.png \
	words/mouse.png \
	words/mouth.png \
	words/movie.png \
	words/mower.png \
	words/mud.png \
	words/mug.png \
	words/mule.png \
	words/muscle.png \
	words/mushroom.png \
	words/music.png \
	words/musician.png \
	words/naked.png \
	words/nap.png \
	words/navel.png \
	words/neck.png \
	words/necklace.png \
	words/needle.png \
	words/nest.png \
	words/net.png \
	words/newspaper.png \
	words/night.png \
	words/nightgown.png \
	words/nine.png \
	words/nose.png \
	words/nostril.png \
	words/notebook.png \
	words/number.png \
	words/nun.png \
	words/nurse.png \
	words/nurse_male.png \
	words/nut.png \
	words/oar.png \
	words/ocean.png \
	words/office.png \
	words/olive.png \
	words/on.png \
	words/one.png \
	words/onion.png \
	words/open.png \
	words/opossum.png \
	words/orange-color.png \
	words/orange.png \
	words/orchid.png \
	words/ostrich.png \
	words/otter.png \
	words/owl.png \
	words/ox.png \
	words/oyster.png \
	words/pacifier.png \
	words/page.png \
	words/pair.png \
	words/pajamas.png \
	words/pal.png \
	words/palm_tree.png \
	words/pan.png \
	words/panda.png \
	words/panther.png \
	words/panties.png \
	words/pants.png \
	words/papaya.png \
	words/paper.png \
	words/parachute.png \
	words/parakeet.png \
	words/parrot.png \
	words/patch.png \
	words/path.png \
	words/paw.png \
	words/pea.png \
	words/peach.png \
	words/peacock.png \
	words/peak.png \
	words/pear.png \
	words/pearl.png \
	words/peck.png \
	words/pedal.png \
	words/pelican.png \
	words/pen.png \
	words/pencil.png \
	words/peony.png \
	words/people.png \
	words/pepper.png \
	words/peppers.png \
	words/pet.png \
	words/petal.png \
	words/petite.png \
	words/phone.png \
	words/piano.png \
	words/picture.png \
	words/pie.png \
	words/pig.png \
	words/pigeon.png \
	words/pill.png \
	words/pillow.png \
	words/pilot.png \
	words/pine.png \
	words/pine_cone.png \
	words/pink.png \
	words/pip.png \
	words/pipe.png \
	words/piranha.png \
	words/pirate.png \
	words/pizza.png \
	words/plane.png \
	words/planet.png \
	words/plant.png \
	words/plate.png \
	words/play.png \
	words/pliers.png \
	words/plow.png \
	words/plum.png \
	words/plumber.png \
	words/pocket.png \
	words/pod.png \
	words/pole.png \
	words/police.png \
	words/pompon.png \
	words/pond.png \
	words/pony.png \
	words/pool.png \
	words/pop.png \
	words/pope.png \
	words/porthole.png \
	words/post.png \
	words/pot.png \
	words/potato.png \
	words/pounce.png \
	words/president.png \
	words/pretty.png \
	words/price.png \
	words/priest.png \
	words/prince.png \
	words/princess.png \
	words/prison.png \
	words/prisoner.png \
	words/prize.png \
	words/pug.png \
	words/pull.png \
	words/pullover.png \
	words/pumpkin.png \
	words/puppy.png \
	words/pyramid.png \
	words/quarrel.png \
	words/queen.png \
	words/question.png \
	words/quilt.png \
	words/quiz.png \
	words/rabbit.png \
	words/rabbit_baby.png \
	words/race.png \
	words/radio.png \
	words/radish.png \
	words/raft.png \
	words/rag.png \
	words/rage.png \
	words/rain.png \
	words/raincoat.png \
	words/rake.png \
	words/ramp.png \
	words/ran.png \
	words/raspberry.png \
	words/rat.png \
	words/razor.png \
	words/read.png \
	words/red.png \
	words/reptile.png \
	words/rhinoceros.png \
	words/rice.png \
	words/ride.png \
	words/rifle.png \
	words/right.png \
	words/rip.png \
	words/rise.png \
	words/river.png \
	words/road.png \
	words/roast.png \
	words/robe.png \
	words/robot.png \
	words/rock.png \
	words/rocket.png \
	words/rolling_pin.png \
	words/roof.png \
	words/room.png \
	words/root.png \
	words/rope.png \
	words/rose.png \
	words/round.png \
	words/rowing.png \
	words/royal.png \
	words/rug.png \
	words/run.png \
	words/sad.png \
	words/saddle.png \
	words/sail.png \
	words/sailor.png \
	words/salamander.png \
	words/salmon.png \
	words/sand.png \
	words/sandals.png \
	words/sandwich.png \
	words/sash.png \
	words/sat.png \
	words/sauce.png \
	words/sausage.png \
	words/scale.png \
	words/scar.png \
	words/scared.png \
	words/scarf.png \
	words/school.png \
	words/school_bag.png \
	words/science.png \
	words/scissors.png \
	words/scorpion.png \
	words/scratch.png \
	words/scream.png \
	words/screw.png \
	words/screwdriver.png \
	words/scribble.png \
	words/sea.png \
	words/seat.png \
	words/see.png \
	words/seed.png \
	words/seven.png \
	words/shadow.png \
	words/shake.png \
	words/shark.png \
	words/shave.png \
	words/shed.png \
	words/sheep.png \
	words/shelf.png \
	words/shell.png \
	words/ship.png \
	words/shirt.png \
	words/shoe.png \
	words/shoelace.png \
	words/shop.png \
	words/shore.png \
	words/short.png \
	words/shovel.png \
	words/shower.png \
	words/shrimp.png \
	words/shrub.png \
	words/shut.png \
	words/shutter.png \
	words/sick.png \
	words/sidewalk.png \
	words/sign.png \
	words/sing.png \
	words/sink.png \
	words/sip.png \
	words/sister.png \
	words/sit.png \
	words/six.png \
	words/sixteen.png \
	words/skate.png \
	words/skeleton.png \
	words/ski.png \
	words/skimmer.png \
	words/skin.png \
	words/skirt.png \
	words/skunk.png \
	words/sky.png \
	words/slam.png \
	words/sled.png \
	words/sleep.png \
	words/sleeve.png \
	words/sleigh.png \
	words/slide.png \
	words/slim.png \
	words/slime.png \
	words/slippers.png \
	words/slope.png \
	words/sloppy.png \
	words/slot.png \
	words/sloth.png \
	words/slug.png \
	words/small.png \
	words/smell.png \
	words/smile.png \
	words/smock.png \
	words/smoke.png \
	words/smooch.png \
	words/snack.png \
	words/snail.png \
	words/snake.png \
	words/sneaker.png \
	words/sniff.png \
	words/snow.png \
	words/soap.png \
	words/sob.png \
	words/sock.png \
	words/soldier.png \
	words/sole.png \
	words/sole_shoe.png \
	words/son.png \
	words/soup.png \
	words/spade.png \
	words/spaghetti.png \
	words/spark.png \
	words/sparrow.png \
	words/spatula.png \
	words/speak.png \
	words/spear.png \
	words/spice.png \
	words/spider.png \
	words/spider_web.png \
	words/spike.png \
	words/spill.png \
	words/spinach.png \
	words/spine.png \
	words/spinning_top.png \
	words/splash.png \
	words/splatter.png \
	words/sponge.png \
	words/spool.png \
	words/spoon.png \
	words/sport.png \
	words/spot.png \
	words/spray.png \
	words/spread.png \
	words/spring.png \
	words/spring_season.png \
	words/sprinkle.png \
	words/square.png \
	words/squash.png \
	words/squat.png \
	words/squid.png \
	words/squirrel.png \
	words/squirt.png \
	words/stack.png \
	words/stage.png \
	words/staircase.png \
	words/stamp.png \
	words/stand.png \
	words/star.png \
	words/stare.png \
	words/starfish.png \
	words/steak.png \
	words/steam.png \
	words/steep.png \
	words/steeple.png \
	words/stem.png \
	words/step.png \
	words/stew.png \
	words/stick.png \
	words/sting.png \
	words/stinky.png \
	words/stitch.png \
	words/stomach.png \
	words/stone.png \
	words/stop.png \
	words/store.png \
	words/stove.png \
	words/straight.png \
	words/strainer.png \
	words/straw.png \
	words/strawberry.png \
	words/stream.png \
	words/street.png \
	words/stretch.png \
	words/string.png \
	words/stripe.png \
	words/strong.png \
	words/student.png \
	words/study.png \
	words/stump.png \
	words/sugar.png \
	words/suit.png \
	words/suitcase.png \
	words/summer.png \
	words/summit.png \
	words/sun.png \
	words/swan.png \
	words/sweat.png \
	words/sweatshirt.png \
	words/swim.png \
	words/table.png \
	words/tablecloth.png \
	words/tadpole.png \
	words/tag.png \
	words/tail.png \
	words/tall.png \
	words/tape_measure.png \
	words/taxi.png \
	words/teach.png \
	words/teacher.png \
	words/tear.png \
	words/teddy.png \
	words/teeth.png \
	words/television.png \
	words/temple.png \
	words/ten.png \
	words/tennis.png \
	words/tent.png \
	words/text.png \
	words/thick.png \
	words/thief.png \
	words/thigh.png \
	words/think.png \
	words/thread.png \
	words/three.png \
	words/throat.png \
	words/throw.png \
	words/thumb.png \
	words/tick.png \
	words/ticket.png \
	words/tiger.png \
	words/time.png \
	words/tin.png \
	words/tire.png \
	words/tired.png \
	words/tissue.png \
	words/toad.png \
	words/toaster.png \
	words/toe.png \
	words/toilet.png \
	words/tomatoe.png \
	words/tongs.png \
	words/tongue.png \
	words/tool.png \
	words/top.png \
	words/torch.png \
	words/touch.png \
	words/towel.png \
	words/toy.png \
	words/trail.png \
	words/train.png \
	words/train_station.png \
	words/trap.png \
	words/trash.png \
	words/tray.png \
	words/treat.png \
	words/tree.png \
	words/triangle.png \
	words/tribe.png \
	words/trip.png \
	words/truck.png \
	words/tube.png \
	words/tulip.png \
	words/tune.png \
	words/turkey.png \
	words/turnip.png \
	words/turtle.png \
	words/tusk.png \
	words/twelve.png \
	words/twin_boys.png \
	words/twin_girls.png \
	words/two.png \
	words/umbrella.png \
	words/under.png \
	words/uniform.png \
	words/van.png \
	words/vapor.png \
	words/vase.png \
	words/vegetable.png \
	words/vein.png \
	words/verdure.png \
	words/vest.png \
	words/vet.png \
	words/viper.png \
	words/vowel.png \
	words/vulture.png \
	words/wag.png \
	words/walk.png \
	words/wall.png \
	words/walnut.png \
	words/wart.png \
	words/wash.png \
	words/wasp.png \
	words/watch.png \
	words/water.png \
	words/wave.png \
	words/wedding.png \
	words/wedge.png \
	words/weight.png \
	words/wet.png \
	words/whale.png \
	words/wheat.png \
	words/wheel.png \
	words/whisk.png \
	words/whisper.png \
	words/white.png \
	words/wide.png \
	words/wife.png \
	words/wig.png \
	words/win.png \
	words/wind.png \
	words/window.png \
	words/window_glass.png \
	words/wing.png \
	words/winter.png \
	words/wolf.png \
	words/woman.png \
	words/wood.png \
	words/word.png \
	words/worker.png \
	words/world.png \
	words/wreath.png \
	words/wrench.png \
	words/wrist.png \
	words/write.png \
	words/yellow.png \
	words/yogurt.png \
	words/yum.png \
	words/zebra.png \
	words/zero.png \
	words/zipper.png \
	words/zoo.png


# introdir = $(pkgdatadir)/@PACKAGE_DATA_DIR@/lang/intro
# intro_DATA = \
# 	intro/a_boy.jpg \
# 	intro/a_girl.jpg \
# 	intro/automn.jpg \
# 	intro/basketball.jpg \
# 	intro/beach2.jpg \
# 	intro/beach.jpg \
# 	intro/birthday_clara.jpg \
# 	intro/birthday_clement.jpg \
# 	intro/blackboard.jpg \
# 	intro/book.jpg \
# 	intro/cantine.jpg \
# 	intro/cat_on_chair.jpg \
# 	intro/christmas_tree.jpg \
# 	intro/clara_and_grandma.jpg \
# 	intro/clara_clement_sabrina_play.jpg \
# 	intro/clara_clown.jpg \
# 	intro/clara_dance.jpg \
# 	intro/clara_diving.jpg \
# 	intro/clara_eats.jpg \
# 	intro/clara_guitar.jpg \
# 	intro/clara_homework.jpg \
# 	intro/clara.jpg \
# 	intro/clara_sea_side.jpg \
# 	intro/clara_ski.jpg \
# 	intro/clara_teeth_brush.jpg \
# 	intro/clement_and_dad.jpg \
# 	intro/clement_drinks.jpg \
# 	intro/clement_is_drawing.jpg \
# 	intro/clement_kayaking.jpg \
# 	intro/climbing_tree.jpg \
# 	intro/dad_iron.jpg \
# 	intro/dad.jpg \
# 	intro/dad_programs.jpg \
# 	intro/djill_piano.jpg \
# 	intro/Earth_Western_Hemisphere.jpg \
# 	intro/Eiffel_Tower_Paris.jpg \
# 	intro/eraser.jpg \
# 	intro/family_dinner.jpg \
# 	intro/fire.jpg \
# 	intro/fishing.jpg \
# 	intro/flower.jpg \
# 	intro/football.jpg \
# 	intro/glue.jpg \
# 	intro/good_afternoon.jpg \
# 	intro/good_evening.jpg \
# 	intro/good_morning.jpg \
# 	intro/good_night.jpg \
# 	intro/grandma_gardening.jpg \
# 	intro/grandma_sewing.jpg \
# 	intro/grandpa_cooking.jpg \
# 	intro/grandpa_newspaper.jpg \
# 	intro/he_is_sick.jpg \
# 	intro/hello_clara.jpg \
# 	intro/hello_clement.jpg \
# 	intro/hello.jpg \
# 	intro/history.jpg \
# 	intro/horse_riding.jpg \
# 	intro/how_do_you_do.jpg \
# 	intro/how_old_are_you.jpg \
# 	intro/i_am_fine.jpg \
# 	intro/is_he_sick.jpg \
# 	intro/mum_cooking.jpg \
# 	intro/mum.jpg \
# 	intro/notebook.jpg \
# 	intro/pancakes.jpg \
# 	intro/Paris-Grand-Palais.jpg \
# 	intro/pencil_case.jpg \
# 	intro/pencil.jpg \
# 	intro/pencil_sharpener.jpg \
# 	intro/pen.jpg \
# 	intro/playground.jpg \
# 	intro/pupils.jpg \
# 	intro/rain.jpg \
# 	intro/reading.jpg \
# 	intro/red_pencil.jpg \
# 	intro/ruler.jpg \
# 	intro/sabrina_sea_side.jpg \
# 	intro/sabrina_sings.jpg \
# 	intro/school_bag.jpg \
# 	intro/school.jpg \
# 	intro/science.jpg \
# 	intro/scissors.jpg \
# 	intro/simon_bicycle.jpg \
# 	intro/sit_down.jpg \
# 	intro/ski_fall.jpg \
# 	intro/snow.jpg \
# 	intro/spring.jpg \
# 	intro/stapler.jpg \
# 	intro/student_walk.jpg \
# 	intro/sunny.jpg \
# 	intro/swimming.jpg \
# 	intro/teacher.jpg \
# 	intro/vacation.jpg \
# 	intro/welcome.jpg \
# 	intro/what_is_your_name.jpg \
# 	intro/who_are_you.jpg

EXTRA_DIST = $(img_DATA) \
	$(wordsimg_DATA) \
	$(intro_DATA) \
	${xml_in_files}
CLEANFILES = $(xml_DATA)
