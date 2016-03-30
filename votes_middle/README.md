# rating with separate tables for objects, users, votes
# something like this:
#
# CREATE TABLE objects (
#  'id' INTEGER,
#  'url' TEXT,
# );

# CREATE TABLE users (
#  'id' INTEGER,
#  'name' TEXT,
#  'login' TEXT,
# );

# CREATE TABLE votes (
#  'id’ INTEGER,
#  'created_at’ DATETIME,
#  'object_id’ INTEGER,
#  'user_id’ INTEGER,
#  'vote’ INTEGER
# );