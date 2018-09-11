# CAHNRS-Email-templates
## Dada Mail Emailing Notes
### Forward to a Friend
Dada Mail's "forward to a friend" messes with the look of the email & just creates it as a webpage. It doesn't include any mechanism to actually forward to a freind 
[https://goo.gl/pLiopM](https://goo.gl/pLiopM)
```
<a href="<!-- tmpl_var forward_to_a_friend_link -->" target="_blank" style="color: #333333; outline: none; text-decoration: underline;">Forward to a Friend</a>
```

### Layout !Important
With this template use "Don't use a Layout" from the Layout tab 
[https://goo.gl/ugtf4n](https://goo.gl/ugtf4n)

## MailChimp Emailing Notes
### Merge Tags:
[All the Merge Tags Cheat Sheet](https://kb.mailchimp.com/merge-tags/all-the-merge-tags-cheat-sheet?_ga=2.31925310.1028200013.1519846782-46907737.1519846782) 

### Ghost lines in Outlook from a MC mailing
Most likely due to the height of something being an odd number. - *Still testing this to confirm* 
[https://goo.gl/12Q9ab](https://goo.gl/12Q9ab) 
[https://goo.gl/vdoXfk](https://goo.gl/vdoXfk) 

EOA: [How Do I Get Rid of the Lines in Outlook Emails?](https://www.emailonacid.com/blog/article/email-development/how-do-i-get-rid-of-the-lines-in-outlook-emails/)


## !Important - Before mailing
**Remove the HTML comments from the email** 
- FIND & REPLACE - in the <head>
- Section comments - in the <body>

### Ubber !Important
**Keep the conditional css code for Outlook in the head** 
Begins with:
```
<!--[if mso]>
<style type="text/css"> 
```
