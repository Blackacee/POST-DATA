# POST-DATA
 
fetch(`/example/submit.json`, {
 method: 'POST',
 body: JSON.stringify({
 email: document.getElementById('example-email').value,
 comment: document.getElementById('example-comment').value
 })
});
