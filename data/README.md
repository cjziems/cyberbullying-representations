# Data
The data is broken up into a features file `X.csv` and a labels file `y.csv`. The file details are as follows.

### X.csv

`FKRA`: Flesch-Kincaid Graid Level metric
`FRE`: Flesch Reading Ease metric
`achieve`: LIWC category
`adverb`: LIWC category
`affect`: LIWC category
`aggr_auth_messages`: How many of the author’s messages were classified as aggressive?
`aggr_follow_up_users`: Of the users who posted a reply in the thread after the author first commented,how many of them had a message classified as aggressive?
`aggr_messages`: How many messages in the thread were classified as aggressive?
`anger`: LIWC category
`anx`: LIWC category
`article`: LIWC category
`assent`: LIWC category
`auth_followers`: number of users who follow author account
`auth_friends`: number of users who are followed by the author account
`auth_verified`: (boolean) indication of author's verified status on Twitter
`author_message_count`: total number of tweets posted by the author between Jan 1 and Jun 10, 2019
`auxverb`: LIWC category
`bi_overlap`: bidirectional overlap between author and target
`bio`: LIWC category
`body`: LIWC category
`cause`: LIWC category
`certain`: LIWC category
`cogmech`: LIWC category
`comp`: VADER compound sentiment score
`conj`: LIWC category
`cross_entropy`: cross entropy of the author's message according to bigram language model of a 4-year snapshot of their timeline
`death`: LIWC category
`discrep`: LIWC category
`down_mentions`: number of times the author mentioned the target between Jan 1 and Jun 10, 2019
`downward_overlap`: downward overlap between author and target
`excl`: LIWC category
`family`: LIWC category
`feel`: LIWC category
`filler`: LIWC category
`follow_up_messages`: How many replies were posted in the thread after the author’s first comment?
`follow_up_users`: How many users posted a reply in the thread after the author’s first comment?
`followers_overlap`: inward overlap between author and target
`friend`: LIWC category
`friends_overlap`: outward overlap between author and target
`funct`: LIWC category
`future`: LIWC category
`health`: LIWC category
`hear`: LIWC category
`home`: LIWC category
`humans`: LIWC category
`i`: LIWC category
`incl`: LIWC category
`ingest`: LIWC category
`inhib`: LIWC category
`insight`: LIWC category
`ipron`: LIWC category
`leisure`: LIWC category
`max_auth_favorites`: What is the largest number of favorites the author received on a messagein the thread?
`max_auth_replies`: What is the largest number of replies the author received on a messagein the thread?
`max_auth_rts`: What is the largest number of retweets the author has received on a mes-sage in the thread?
`mention_overlap`: jaccard index between M_a (accounts mentioned by author) and M_t (accounts mentioned by target)
`message_count`: How many messages have been shared in the thread?
`money`: LIWC category
`motion`: LIWC category
`multiset_mention_overlap`: multiset mention overlap discussed in the paper
`neg`: VADER negative sentiment score
`negate`: LIWC category
`negemo`: LIWC category
`neu`: VADER neutral sentiment score
`new_words_ratio`: ratio of words in post which have never before been seen in the author's timeline
`nonfl`: LIWC category
`num_chars`: number of characters in tweet
`num_unique_terms`: number of unique terms in tweet
`num_words`: number of words in tweet
`number`: LIWC category
`past`: LIWC category
`percept`: LIWC category
`pos`: LIWC category
`posemo`: LIWC category
`ppron`: LIWC category
`preps`: LIWC category
`present`: LIWC category
`pronoun`: LIWC category
`quant`: LIWC category
`relativ`: LIWC category
`relig`: LIWC category
`sad`: LIWC category
`see`: LIWC category
`sexual`: LIWC category
`shehe`: LIWC category
`social`: LIWC category
`space`: LIWC category
`swear`: LIWC category
`targ_followers`: number of users who follow target account
`targ_friends`: number of users who are followed by the target account
`targ_verified`: (boolean) indication of author's verified status on Twitter
`target_message_count`: total number of tweets posted by the target between Jan 1 and Jun 10, 2019
`tentat`: LIWC category
`they`: LIWC category
`time`: LIWC category
`timeline_sim`: similarity between author and target timelines, computed using cosine similarity
`up_mentions`: number of times the target mentioned the author between Jan 1 and Jun 10, 2019
`verb`: LIWC category
`we`: LIWC category
`work`: LIWC category
`you`: LIWC category

### y.csv

`auth_id`: Twitter assigned ID of author account
`targ_id`: Twitter assigned ID of target account
`aggr`: y label on aggression
`auth_power`: y label on author power
`bully`: y label on cyberbullying
`harm`: y label on harmful intent
`peer`: y label on visibility among peers
`rep`: y label on repetition
`targ_power`: y label on target power
