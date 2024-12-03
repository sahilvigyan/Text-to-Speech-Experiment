This project is an experiment regarding voice generation in computers. There will be experiments for several phenomenon regarding voice (Human spoken language). The goal is to uncover some secrets regarding the topics like 
1. Accents
2. Emotions in Voice
3. Differences between voices of different persons regarding how their tone sounds

Module 1:
	In this module we will be trying to regenerate someone else voice just by concatenating a few prerecorded words. 

	this is a cat
	that is a ball
	cat is not ball
	this cat is not that ball
	ball is not cat and cat is not ball

	Unique words are,
	this, is, a, cat, that, ball, not, and

	Discovery 1:
	"During speaking an entire sentence, it's not just the words being spoken, it's a couple of phrases getting being spoken."
	For example, in the sentence - This is a cat. The way we/me generally pronounce it is like "This is-a cat." 

	For example, 
	Finding a way to find out in a sentence which words are/could be taken as a phrase.

Module 2:
	In this module we will be trying to find out a way to find out in a sentence which words are/could be taken as a phrase.

	Discovery 2:
	We can take any set of conjecutive words randomly as a phrase in a sentnece and all these random ways works fine. 

	this is a cat. 

	Here are a few examples the way we will be defining the conjuction_time between words while getting concatenated. 
	this, cnj_-0.2, is, cnj_-0.2, a cnj_0, cat
	this, cnj_-0.2, is, cnj_0, a, cnj_0.2, cat 
	this, cnj_0, is, cnj_0, a, cnj_, -0.2, cat

Module 3:
	In this module we will be applying differnet speeds at different words randomly and see if it creates some realistic sounding speaks. 

	Discovery 3:
	By applying differnet speeds at different words randomly, it generates more human like speeches. 
	
	

