---
name: Lyrics addition request
about: To add new song lyrics to the repository
title: "[Lyrics addition]"
labels: ''
assignees: v9y

---
Use the template below to submit your lyrics. Copy the template in the box and use it for lyrics submission as described below.

Add a new file in the docs folder and paste the template. Name the file "stitle.isb.txt". Fill out the lyrics submission as suggested below. Commit to a new branch and submit for approval and merge.

1. Fill out all the fields between the curly brackets {} in the way they are normally spelled in English (do not use iTrans for these). Fill out as many fields as you can. Song title (stitle) is required.

2. All fields starting with % are optional except "Contributor". For Tags, write the mood, genre, or category of the song, separated by commas. Audio On field is used by editors to validate the lyrics. Feel free to provide a YouTube or another audio link where they can listen to the song. 

3. Write the lyrics between "#indian" and "#endindian" tags. Use iTrans or HiTrans notations. Check out https://www.giitaayan.com for the scheme and the HiTrans tool to try converting your notation.

<pre>
% ITRANS Song #
% 
\startsong
\stitle{}%
\film{}%
\year{}%
\starring{}%
\singer{}%
\music{}%
\lyrics{}%
% 
% Tags: 
% Audio on: 
% Contributor: 
% Date: 
% Series: 
% Comments: 
% generated using www.giitaayan.com
%
\printtitle
#indian
%

%
#endindian
\endsong
</pre>
