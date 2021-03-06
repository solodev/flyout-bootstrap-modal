# flyout-bootstrap-modal
By default, bootstrap modals will appear in the center of the screen with a slight animation from top-down. However, depending on your UI or overall design, you may want to have modals flyout from the sides.

## Tutorial
For detailed instruction's, view Solodev's [How to Create a Flyout Bootstrap Modal](https://www.solodev.com/blog/web-design/bootstrap/how-to-create-a-flyout-bootstrap-modal.stml) article.

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/vr5yjbk2/).

## HTML
The tutorial contains the following basic HTML markup.

```
<!-- Button to open the Modal -->
<div class="col-sm-3 col-xl-2 order-1 order-sm-2 mt-4 float-right">
  <a href="#" data-toggle="modal" data-target="#flyoutmodal" class="btn btn-dark mt-2 w-md-100 text-center">Launch Modal</a>
</div>

<!-- Modal -->
<div class="modal" id="flyoutmodal" tabindex="-1" role="dialog" aria-hidden="true">
  <div class="modal-dialog fadeInRight animated ml-auto" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLongTitle">May the Force be with you</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body">
        <p>Kid, I've flown from one side of this galaxy to the other. I've seen a lot of strange stuff, but I've never seen anything to make me believe there's one all-powerful Force controlling everything. There's no mystical energy field that controls my destiny. It's all a lot of simple tricks and nonsense. I want to come with you to Alderaan. There's nothing for me here now. I want to learn the ways of the Force and be a Jedi, like my father before me.</p>
        <p>I have traced the Rebel spies to her. Now she is my only link to finding their secret base. The Force is strong with this one. I have you now. Still, she's got a lot of spirit. I don't know, what do you think?</p>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Submit</button>
      </div>
    </div>
  </div>
</div>

```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
```