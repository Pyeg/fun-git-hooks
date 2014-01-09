Fun git hooks
=============

Some scripts to do funny stuff when you commit stuff to your git. 

While Listening:
----------------

This hook appends the name of the song you are listening to, to your git commit messages:

- First thing to do is to rename it to commit-msg and instead of commit-msg.while-listening
- Then move it in .git/hooks in your repo(s), put it in as much repos as you want.
- Then open the file and edit your lastfm_key and lastfm_user strings.
- You can get your last.fm key from here, http://www.last.fm/api/accounts

Now all your future commits in that repo will have the new message appended to them.

