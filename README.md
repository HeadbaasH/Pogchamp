from random import choice

animes = [['Demon Slayer', 'action', 'shonen', 'series'],
        ['Haikyuu', 'sports', 'friendly', 'series'],
        ['Attack on Titans', 'action', 'political', 'series'],
        ['Red Line', 'action', 'sport', 'movie'],
        ['Spirited Away', 'fantasy', 'friendly', 'movie']]

print("What mood are you in for today's anime?")
mood = input()

for item in animes:
    if mood in {item[1], item[2], item[3]}:
        print(mood + ' anime: ' + item[0])
