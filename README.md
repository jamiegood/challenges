challenges
==========

SELECT * FROM `challenge` LEFT JOIN challenge_user 
ON 
challenge.id = challenge_user.challenge_id 
LEFT JOIN user
ON
challenge_user.user_id = user.id
WHERE user.id = 1