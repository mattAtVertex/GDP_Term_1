# Weapon Pickups

<p><iframe title="YouTube video player" src="https://www.youtube.com/embed/8-p8Gw1ezhs?si=kEl8L_xIIG6_F81F" width="800" height="500" allowfullscreen="allowfullscreen" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"></iframe></p>
<p><strong>Note: The pickup blueprint will lose its reference to the class if you close the editor. We fix this in a later video.&nbsp;</strong></p>
<p><strong>Here are screenshots of the updated code:<br><img src="https://vertexschool.instructure.com/courses/462/files/27930/preview?verifier=1PIN7oZHpiKIrMTQsoMrX5MF9tWEFnCgeF48gOyS" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/462/files/27930" data-api-returntype="File"><br></strong></p>
<p><strong>What we do to store the reference based on public booleans and assigning the correct class in a public variable.&nbsp;</strong></p>
<p><strong>Here are the variables and which ones are set to Instance Editable (this means you can edit them in the details panel when you place the Blueprint in the level</strong></p>
<p><strong><img src="https://vertexschool.instructure.com/courses/462/files/27931/preview?verifier=0Sno5vbFbrEDXOkWVfSM8pFcHqfNGr3bmMs0PqyN" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/462/files/27931" data-api-returntype="File"></strong></p>
<p><strong>We then initialize the event "Set Weapon Type" in Begin Play. This ensures that the Blueprint retains its class reference.&nbsp;</strong></p>
<p><strong><img src="https://vertexschool.instructure.com/courses/462/files/27932/preview?verifier=yuvGwuk6rfmlusDulln7OuJ1QC1MvDLJqVFqG4JR" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/462/files/27932" data-api-returntype="File"></strong></p>
<p>&nbsp;</p>