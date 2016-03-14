# words-path

## Outline
The problem is to find “word paths”. What this means is that you find a path from one word to 
another word, changing one letter each step, and each intermediate word must be in the 
dictionary.

## Some example solutions:
```
rial ­> real ­> feal ­> foal ­> foul ­> foud
yagi ­> yali ­> pali ­> palp ­> paup ­> plup ­> blup
jina ­> pina ­> pint ­> pent ­> peat ­> prat ­> pray 
fike ­> fire ­> fare ­> care ­> carp ­> camp
```

## Get help to run the script
```
ruby words_path.rb -h
```

## Example of running the script
```
ruby words_path.rb -f /usr/share/dict/words -s rial -e foud
```

## Requirements
Ruby 2.0 or greater

