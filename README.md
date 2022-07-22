import bitches

class Attributes:
	def __init__(self) -> None:
		bitches.get('bitches')
		
	def contact(self):
	    discord  = "&! Tekky#1337"
	    telegram = "t.me/xtekky"
	    proton   = "xtekky@protonmail.com"
	    
	    return discord, telegram, proton

	def life(self):
		langs         = ['French', 'German', 'Spanish', 'English']
		nationalities = self.langs.remove('French', 'English').append('Korean')
		age           = 16
		
		return langs, nationalities, age
		
	def coding(self):
		langs = {
			'expert':   ['python'],
			'intermediate': ['go'],
			'learning': ['js', 'c#']
		}
		specialities  = ['web reverse engineering', 'discord bots'. 'backend']
		environnement = ['vscode', 'pycharm']
		
		return langs, specialities, environnement
		
	def projects(self):
		discord   = ['HQ Gen', 'Raid Toolkit']
		tiktok    = ['view bot', 'Algorithms']
		instagram = ['Gen', 'Botting']
		twitch    = ['Free Gen', 'Everything u can think of']
		website   = ['Full TikTok API', 'Backend']
		
		return discord, tiktok, instagram, twitch, website
