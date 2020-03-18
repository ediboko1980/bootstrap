---
layout: docs
title: Forms
description: Use Rockets's form elements such as text inputs, textareas, file uploads and many more to get input from you users
group: components
toc: true
---

## Form example

The following example is a classical form for login or register pages:

{{< example >}}
<form>
    <div class="form-group">
        <label for="exampleInputEmail1">Email address</label>
        <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email">
        <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
    </div>
    <div class="form-group">
        <label for="exampleInputPassword1">Password</label>
        <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
    </div>
    <div class="form-group form-check mb-3">
        <label class="form-check-label">
            <input class="form-check-input" type="checkbox">
            <span class="form-check-sign"></span>
            Check me out
        </label>
    </div>
    <button type="submit" class="btn btn-primary">Submit</button>
</form>
{{< /example >}}

## Select input

The following example is how the select inputs look and can be used:

{{< example >}}
<div class="form-group">
    <label for="exampleFormControlSelect1">Example select</label>
    <select class="custom-select" id="exampleFormControlSelect1">
    <option>1</option>
    <option>2</option>
    <option>3</option>
    <option>4</option>
    <option>5</option>
    </select>
</div>
{{< /example >}}


## Multiple select

The following example is how the select inputs look and can be used:

{{< example >}}
<div class="form-group">
    <label for="exampleFormControlSelect2">Example multiple select</label>
    <select multiple class="custom-select" id="exampleFormControlSelect2">
    <option>Bootstrap</option>
    <option>VueJs</option>
    <option>Angular</option>
    <option>React</option>
    <option>NodeJs</option>
    </select>
</div>
{{< /example >}}

## Textarea

The following example is how textareas can be used:

{{< example >}}
<div class="form-group">
    <label for="exampleFormControlTextarea2">Example textarea</label>
    <textarea class="form-control" id="exampleFormControlTextarea2" rows="3"></textarea>
</div>
{{< /example >}}


## File upload

The following example is how file uploads can be used:

{{< example >}}
<div class="custom-file">
    <input type="file" class="custom-file-input" id="customFile">
    <label class="custom-file-label" for="customFile">Choose file</label>
</div>
{{< /example >}}

## Checkboxes

### Square style

{{< example >}}
<div class="form-check mb-3">
    <label class="form-check-label">
        <input class="form-check-input" type="checkbox">
        <span class="form-check-sign"></span>
        Unchecked
    </label>
</div>
<div class="form-check">
    <label class="form-check-label">
        <input class="form-check-input" type="checkbox" checked>
        <span class="form-check-sign"></span>
        Checked
    </label>
</div>
<div class="form-check disabled">
    <label class="form-check-label">
        <input class="form-check-input" type="checkbox" disabled>
        <span class="form-check-sign"></span>
        Disabled Unchecked
    </label>
</div>
<div class="form-check disabled">
    <label class="form-check-label">
        <input class="form-check-input" type="checkbox" checked disabled>
        <span class="form-check-sign"></span>
        Disabled Checked
    </label>
</div>
{{< /example >}}

### Round style

{{< example >}}
<div class="form-check round-check mb-3">
    <label class="form-check-label">
        <input class="form-check-input" type="checkbox">
        <span class="form-check-sign"></span>
        Unchecked
    </label>
</div>
<div class="form-check round-check">
    <label class="form-check-label">
        <input class="form-check-input" type="checkbox" checked>
        <span class="form-check-sign"></span>
        Checked
    </label>
</div>
<div class="form-check round-check disabled">
    <label class="form-check-label">
        <input class="form-check-input" type="checkbox" disabled>
        <span class="form-check-sign"></span>
        Disabled Unchecked
    </label>
</div>
<div class="form-check round-check disabled">
    <label class="form-check-label">
        <input class="form-check-input" type="checkbox" checked disabled>
        <span class="form-check-sign"></span>
        Disabled Checked
    </label>
</div>
{{< /example >}}

## Radio buttons

{{< example >}}
<div class="form-check form-check-radio">
    <label class="form-check-label">
        <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios1" value="option1">
        <span class="form-check-sign"></span>
        Radio is off
    </label>
</div>
<div class="form-check form-check-radio">
    <label class="form-check-label">
        <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios2" value="option2" checked>
        <span class="form-check-sign"></span>
        Radio is on
    </label>
</div>
<div class="form-check form-check-radio disabled">
    <label class="form-check-label">
        <input class="form-check-input" type="radio" name="exampleRadios1" id="exampleRadios3" value="option3" disabled>
        <span class="form-check-sign"></span>
        Disabled radio is off
    </label>
</div>
<div class="form-check form-check-radio disabled">
    <label class="form-check-label">
        <input class="form-check-input" type="radio" name="exampleRadios1" id="exampleRadios4" value="option4" disabled checked>
        <span class="form-check-sign"></span>
        Disabled radio is on
    </label>
</div>
{{< /example >}}
