# Top Header

## Second Header
Hello this is text

- **Bullet one**
- Bullet two

### Ideas
https://github.com/fivethirtyeight/data/blob/master/fight-songs/fight-songs.csv
- Are these fight songs played before or after the game and does it depend on if the team won?
- How many fight songs are more than a minute long?
def song_length(sec):
    count = 0
    for line in open('fight-songs.csv'):
        if sec_duration >= sec:
            count += 1
    print(count)


https://github.com/fivethirtyeight/data/blob/master/foul-balls/foul-balls.csv
- Does the weather factor in to the amount of foul balls hit per game?
- Does the time of the game affect the amount of foul balls; does it matter if it's the post-season or regular season?