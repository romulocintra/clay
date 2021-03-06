---
title: "Cards"
---

<article>

### Horizontal Card with autofit-col-*

<p>Use <code>card-row</code> with <code>autofit-col-expand</code> and <code>autofit-col</code> to create a number of custom horizontal cards. <code>autofit-col-expand</code> fills the remaining space and <code>autofit-col</code> is only as wide as its content inside.</p>

```html
<div class="card-row">
    <div class="autofit-col">
        <section class="autofit-section"></section>
    </div>
    <div class="autofit-col autofit-col-expand">
        <section class="autofit-section"></section>
    </div>
</div>
```

<div class="col-md-6">
	<div class="card card-horizontal">
		<div class="card-body">
			<div class="card-row">
				<div class="autofit-col" style="background-color:aliceblue;">
					<span class="sticker">
						<span class="inline-item">
							<svg aria-hidden="true" class="lexicon-icon lexicon-icon-folder">
								<use xlink:href="/images/icons/icons.svg#folder" />
							</svg>
						</span>
					</span>
				</div>
				<div class="autofit-col autofit-col-expand autofit-col-gutters" style="background-color:antiquewhite;">
					<section class="autofit-section">
						<span>Fills remaining space.</span>
					</section>
				</div>
			</div>
		</div>
	</div>
</div>

<p>Two <code>.autofit-col</code>'s no <code>.autofit-col-expand</code>.</p>

```html
<div class="card-row">
    <div class="autofit-col">
        <section class="autofit-section"></section>
    </div>
    <div class="autofit-col">
         <section class="autofit-section"></section>
    </div>
</div>
```

<div class="col-md-6">
	<div class="card card-horizontal">
		<div class="card-body">
			<div class="card-row">
				<div class="autofit-col" style="background-color:aliceblue;">
					<span class="sticker">
						<span class="inline-item">
							<svg aria-hidden="true" class="lexicon-icon lexicon-icon-folder">
								<use xlink:href="/images/icons/icons.svg#folder" />
							</svg>
						</span>
					</span>
				</div>
				<div class="autofit-col autofit-col-gutters" style="background-color:antiquewhite;">
					<span>Only as wide as this text.</span>
				</div>
			</div>
		</div>
	</div>
</div>

<p>Two <code>.autofit-col-expand</code>'s no <code>.autofit-col</code>.</p>

```html
<div class="card-row">
    <div class="autofit-col autofit-col-expand">
        <section class="autofit-section"></section>
    </div>
    <div class="autofit-col autofit-col-expand">
        <section class="autofit-section"></section>
    </div>
</div>
```

<div class="col-md-6">
	<div class="card card-horizontal">
		<div class="card-body">
			<div class="card-row">
				<div class="autofit-col autofit-col-expand" style="background-color:aliceblue;">
					<section class="autofit-section">
						<span class="sticker">
							<span class="inline-item">
								<svg aria-hidden="true" class="lexicon-icon lexicon-icon-folder">
									<use xlink:href="/images/icons/icons.svg#folder" />
								</svg>
							</span>
						</span>
					</section>
				</div>
				<div class="autofit-col autofit-col-expand autofit-col-gutters" style="background-color:antiquewhite;">
					<section class="autofit-section">
						<span>This will split the space in half.</span>
					</section>
				</div>
			</div>
		</div>
	</div>
</div>

</article>

<article>

### Padded Horizontal Cards

<p>Nest <code>card-row</code> in <code>card-body</code> on to add some spacing around a horizontal card.</p>

```html
<div class="card-body">
    <div class="card-row"></div>
</div>
```

<div class="col-md-6">
	<div class="card card-horizontal">
		<div class="card-body">
			<div class="card-row">
				<div class="autofit-col">
					<img alt="thumbnail" class="card-item-first" src="/images/thumbnail_placeholder.gif" style="width: 121px;">
				</div>
				<div class="autofit-col autofit-col-expand autofit-col-gutters">
					<section class="autofit-section">
						<h3 class="card-title">So ristretto cappuccino</h3>
						<p class="card-text">Wings eu, pumpkin spice robusta.</p>
					</section>
				</div>
			</div>
		</div>
	</div>
</div>

</article>

<article>

### Truncating Text Inside Card

<p>Add class <code>text-truncate</code> on whatever text you want to be truncated.</p>

<div class="col-md-6">
	<div class="card card-horizontal">
		<div class="card-body">
			<div class="card-row">
				<div class="autofit-col">
					<img alt="thumbnail" class="card-item-first" src="/images/thumbnail_placeholder.gif" style="width: 150px;">
				</div>
				<div class="autofit-col autofit-col-expand autofit-col-gutters">
					<section class="autofit-section">
						<h3 class="card-title">So ristretto cappuccino</h3>
						<p class="card-text">
							<span class="text-truncate-inline">
								<span class="text-truncate">Wings eu, pumpkin spice robusta, kopi-luwak mocha caffeine froth grounds.</span>
							</span>
						</p>
					</section>
				</div>
			</div>
		</div>
	</div>
</div>

<div class="col-md-12">
	<ul class="list-unstyled row">
		<li class="col-md-6">
			<div class="card card-horizontal card-type-directory">
				<div class="card-body">
					<div class="card-row">
						<div class="autofit-col">
							<span class="sticker">
								<span class="inline-item">
									<svg aria-hidden="true" class="lexicon-icon lexicon-icon-folder">
										<use xlink:href="/images/icons/icons.svg#folder" />
									</svg>
								</span>
							</span>
						</div>
						<div class="autofit-col autofit-col-expand autofit-col-gutters">
							<section class="autofit-section">
								<h3 class="card-title" title="ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual">
									<span class="text-truncate-inline">
										<span class="text-truncate">ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual</span>
									</span>
								</h3>
							</section>
						</div>
						<div class="autofit-col">
							<div class="dropdown dropdown-action">
								<a aria-expanded="false" aria-haspopup="true" class="component-action dropdown-toggle" data-toggle="dropdown" href="#1" role="button">
									<svg aria-hidden="true" class="lexicon-icon lexicon-icon-ellipsis-v">
										<use xlink:href="/images/icons/icons.svg#ellipsis-v" />
									</svg>
								</a>
								<ul class="dropdown-menu dropdown-menu-right">
									<li><a class="dropdown-item" href="#1">Download</a></li>
									<li><a class="dropdown-item" href="#1">Edit</a></li>
									<li><a class="dropdown-item" href="#1">Move</a></li>
									<li><a class="dropdown-item" href="#1">Checkout</a></li>
									<li><a class="dropdown-item" href="#1">Permissions</a></li>
									<li><a class="dropdown-item" href="#1">Move to Recycle Bin</a></li>
								</ul>
							</div>
						</div>
					</div>
				</div>
			</div>
		</li>
		<li class="col-md-6">
			<div class="card card-horizontal card-type-directory">
				<div class="card-body">
					<div class="card-row">
						<div class="autofit-col">
							<span class="sticker">
								<span class="inline-item">
									<svg aria-hidden="true" class="lexicon-icon lexicon-icon-folder">
										<use xlink:href="/images/icons/icons.svg#folder" />
									</svg>
								</span>
							</span>
						</div>
						<div class="autofit-col autofit-col-expand autofit-col-gutters">
							<section class="autofit-section">
								<h3 class="card-title" title="Folder 01">Folder 01</h3>
							</section>
						</div>
						<div class="autofit-col">
							<div class="dropdown dropdown-action">
								<a aria-expanded="false" aria-haspopup="true" class="component-action dropdown-toggle" data-toggle="dropdown" href="#1" role="button">
									<svg aria-hidden="true" class="lexicon-icon lexicon-icon-ellipsis-v">
										<use xlink:href="/images/icons/icons.svg#ellipsis-v" />
									</svg>
								</a>
								<ul class="dropdown-menu dropdown-menu-right">
									<li><a class="dropdown-item" href="#1">Download</a></li>
									<li><a class="dropdown-item" href="#1">Edit</a></li>
									<li><a class="dropdown-item" href="#1">Move</a></li>
									<li><a class="dropdown-item" href="#1">Checkout</a></li>
									<li><a class="dropdown-item" href="#1">Permissions</a></li>
									<li><a class="dropdown-item" href="#1">Move to Recycle Bin</a></li>
								</ul>
							</div>
						</div>
					</div>
				</div>
			</div>
		</li>
		<li class="col-md-6">
			<div class="card card-horizontal card-type-directory">
				<div class="card-body">
					<div class="card-row">
						<div class="autofit-col">
							<span class="sticker">
								<span class="inline-item">
									<svg aria-hidden="true" class="lexicon-icon lexicon-icon-folder">
										<use xlink:href="/images/icons/icons.svg#folder" />
									</svg>
								</span>
							</span>
						</div>
						<div class="autofit-col autofit-col-expand autofit-col-gutters">
							<section class="autofit-section">
								<h3 class="card-title" title="Folder 02">
									<span class="text-truncate-inline">
										<span class="text-truncate">Folder 02</span>
									</span>
								</h3>
							</section>
						</div>
						<div class="autofit-col">
							<div class="dropdown dropdown-action">
								<a aria-expanded="false" aria-haspopup="true" class="component-action dropdown-toggle" data-toggle="dropdown" href="#1" role="button">
									<svg aria-hidden="true" class="lexicon-icon lexicon-icon-ellipsis-v">
										<use xlink:href="/images/icons/icons.svg#ellipsis-v" />
									</svg>
								</a>
								<ul class="dropdown-menu dropdown-menu-right">
									<li><a class="dropdown-item" href="#1">Download</a></li>
									<li><a class="dropdown-item" href="#1">Edit</a></li>
									<li><a class="dropdown-item" href="#1">Move</a></li>
									<li><a class="dropdown-item" href="#1">Checkout</a></li>
									<li><a class="dropdown-item" href="#1">Permissions</a></li>
									<li><a class="dropdown-item" href="#1">Move to Recycle Bin</a></li>
								</ul>
							</div>
						</div>
					</div>
				</div>
			</div>
		</li>
		<li class="col-md-6">
			<div class="card card-horizontal card-type-directory">
				<div class="card-body">
					<div class="card-row">
						<div class="autofit-col">
							<span class="sticker">
								<span class="inline-item">
									<svg aria-hidden="true" class="lexicon-icon lexicon-icon-folder">
										<use xlink:href="/images/icons/icons.svg#folder" />
									</svg>
								</span>
							</span>
						</div>
						<div class="autofit-col autofit-col-expand autofit-col-gutters">
							<section class="autofit-section">
								<h3 class="card-title" title="Folder 03">
									<span class="text-truncate-inline">
										<span class="text-truncate">Folder 03</span>
									</span>
								</h3>
							</section>
						</div>
						<div class="autofit-col">
							<div class="dropdown dropdown-action">
								<a aria-expanded="false" aria-haspopup="true" class="component-action dropdown-toggle" data-toggle="dropdown" href="#1" role="button">
									<svg aria-hidden="true" class="lexicon-icon lexicon-icon-ellipsis-v">
										<use xlink:href="/images/icons/icons.svg#ellipsis-v" />
									</svg>
								</a>
								<ul class="dropdown-menu dropdown-menu-right">
									<li><a class="dropdown-item" href="#1">Download</a></li>
									<li><a class="dropdown-item" href="#1">Edit</a></li>
									<li><a class="dropdown-item" href="#1">Move</a></li>
									<li><a class="dropdown-item" href="#1">Checkout</a></li>
									<li><a class="dropdown-item" href="#1">Permissions</a></li>
									<li><a class="dropdown-item" href="#1">Move to Recycle Bin</a></li>
								</ul>
							</div>
						</div>
					</div>
				</div>
			</div>
		</li>
	</ul>
</div>

</article>

<article>

### Card Row Content Alignment Helpers

<p>Vertically align content by setting <code>justify-content</code> to <code>flex-start</code>, <code>center</code>, or <code>flex-end</code> on <code>autofit-col</code>.</p>

<p>Horizontally align content by setting <code>text-align</code> to <code>left</code>, <code>center</code>, or <code>right</code> on <code>autofit-col</code>.</p>

<p>You can also use the Bootstrap 4's helper classes <code>justify-content-start</code>, <code>justify-content-center</code>, or <code>justify-content-end</code> on <code>card-row</code> to align content in all columns inside the row.</p>

<div class="col-md-6">
	<div class="card card-horizontal">
		<div class="card-row">
			<div class="justify-content-start autofit-col autofit-col-expand">
				<section class="autofit-section">top</section>
			</div>
			<div class="autofit-col autofit-col-expand">
				<section class="autofit-section">middle</section>
			</div>
			<div class="justify-content-end autofit-col autofit-col-expand">
				<section class="autofit-section">
					bottom
				</section>
			</div>
		</div>
	</div>
</div>

<div class="col-md-6">
	<div class="card card-horizontal">
		<div class="card-row">
			<div class="autofit-col autofit-col-expand text-left">
				<section class="autofit-section">
					left
				</section>
			</div>
			<div class="autofit-col autofit-col-expand">
				<section class="autofit-section">
					center
				</section>
			</div>
			<div class="autofit-col autofit-col-expand text-right">
				<section class="autofit-section">
					right
				</section>
			</div>
		</div>
	</div>
</div>

<p>Add gutters to a specific card card column by using the class <code>autofit-col-gutters</code>.</p>

<div class="col-md-6">
	<div class="card card-horizontal">
		<div class="card-row">
			<div class="autofit-col">
				<img alt="thumbnail" class="card-item-first" src="/images/thumbnail_placeholder.gif" style="width: 150px;">
			</div>
			<div class="autofit-col autofit-col-expand autofit-col-gutters">
				<section class="autofit-section">
					<h3 class="card-title">So ristretto cappuccino</h3>
					<p class="card-text">Wings eu, pumpkin spice robusta.</p>
				</section>
			</div>
		</div>
	</div>
</div>

</article>

<article>

### Card Helper Classes

<p>Use classes <code>rounded</code>, <code>rounded-circle</code>, or <code>rounded-0</code> on the card to quickly shape the borders.</p>

<div class="row">
	<div class="clay-site-horizontal-card col-md-4">
		<div class="card card-horizontal rounded">
			<div class="card-row">
				<div class="autofit-col autofit-col-expand">
					<section class="autofit-section">
						autofit-col-expand
					</section>
				</div>
				<div class="autofit-col autofit-col-expand">
					<section class="autofit-section">
						autofit-col-expand
					</section>
				</div>
			</div>
		</div>
	</div>
	<div class="clay-site-horizontal-card col-md-4">
		<div class="card card-horizontal rounded-circle">
			<div class="card-row">
				<div class="autofit-col autofit-col-expand" style="overflow:hidden;">
					<section class="autofit-section">
						<img alt="thumbnail" class="card-item-first" src="/images/thumbnail_placeholder.gif">
					</section>
				</div>
				<div class="autofit-col autofit-col-expand">
					<section class="autofit-section">
						autofit-col-expand
					</section>
				</div>
			</div>
		</div>
	</div>
	<div class="clay-site-horizontal-card col-md-4">
		<div class="card card-horizontal rounded-0">
			<div class="card-row">
				<div class="autofit-col autofit-col-expand">
					<section class="autofit-section">
						autofit-col-expand
					</section>
				</div>
				<div class="autofit-col autofit-col-expand">
					<section class="autofit-section">
						autofit-col-expand
					</section>
				</div>
			</div>
		</div>
	</div>
</div>

<p>Use classes <code>card-item-first</code> and <code>card-item-last</code> on elements that appear at the beginning or ending of your card. It styles the border-radius to match the card's border-radius. These classes work similar to Bootstrap 4's <code>.card-img-top</code> and <code>.card-img-bottom</code> but also covers left and right.</p>

<div class="row">
	<div class="col-md-4 col-6">
		<div class="card card-rounded">
			<div class="aspect-ratio card-item-first">
				<img alt="thumbnail" class="aspect-ratio-item-fluid" src="/images/thumbnail_hot_air_ballon.jpg">
			</div>
			<div class="card-body" style="text-align:center;">
				<h3 class="card-title">Joe Bloggs</h3>
				<p class="card-subtitle">Administrator</p>
				<p class="card-text">Wings eu, pumpkin spice robusta, kopi-luwak mocha caffeine froth grounds.</p>
			</div>
		</div>
	</div>
	<div class="col-md-6 col-sm-12 col-12">
		<div class="card card-horizontal card-rounded">
			<div class="card-row">
				<div class="autofit-col autofit-col-expand autofit-col-gutters">
					<section class="autofit-section">
						<h3 class="card-title">Space Program</h3>
						<div class="card-divider"></div>
						<p class="card-text">Because you live life on the edge of space.</p>
					</section>
				</div>
				<div class="autofit-col">
					<img class="card-item-last" src="/images/thumbnail_dock.jpg" style="width: 150px;" />
				</div>
			</div>
		</div>
	</div>
</div>

</article>

<article>

### Card Dividers

<p>Use <code>`<div class="card-divider"></div>`</code> to create a horizontal division between content inside a card.</p>

<div class="col-md-6">
	<div class="card card-horizontal">
		<div class="card-row">
			<div class="autofit-col autofit-col-expand">
				<section class="autofit-section">
					autofit-col-expand
				</section>
			</div>
			<div class="autofit-col autofit-col-expand">
				<section class="autofit-section">
					<h3 class="card-title">Title</h3>
					<div class="card-divider"></div>
					<p class="card-text">autofit-col-expand</p>
				</section>
			</div>
		</div>
	</div>
</div>

</article>

<article>

### Clickable Checkbox Card

<p>To make the whole card clickable just wrap the checkbox and card in:</p>

<div class="row">
	<div class="col-4">
		<div class="card-type-asset form-check form-check-card form-check-top-left image-card">
			<div class="card">
				<div class="aspect-ratio card-item-first">
					<label class="form-check-label">
						<input class="form-check-input" type="checkbox">
						<span class="sticker sticker-bottom-left sticker-danger">JPG</span>
					</label>
				</div>
				<div class="card-body">
					<div class="card-row">
						<div class="autofit-col autofit-col-expand">
							<section class="autofit-section">
								<h3 class="card-title">
									<span class="text-truncate-inline">
										<span class="text-truncate">Aldcott Gage George Polwarth-Kitchener</span>
									</span>
								</h3>
								<p class="card-subtitle" title="empty.jpg">
									<span class="text-truncate-inline">
										<a class="text-truncate">empty.jpg</a>
									</span>
								</p>
								<div class="card-detail">
									<span class="label label-success">
										<span class="label-item label-item-expand">Approved</span>
									</span>
								</div>
							</section>
						</div>
						<div class="autofit-col">
							<div class="dropdown dropdown-action">
								<a aria-expanded="false" aria-haspopup="true" class="component-action dropdown-toggle" data-toggle="dropdown" href="#1" role="button">
									<svg aria-hidden="true" class="lexicon-icon lexicon-icon-ellipsis-v">
										<use xlink:href="/images/icons/icons.svg#ellipsis-v" />
									</svg>
								</a>
								<ul class="dropdown-menu dropdown-menu-right">
									<li><a class="dropdown-item" href="#1">Download</a></li>
									<li><a class="dropdown-item" href="#1">Edit</a></li>
									<li><a class="dropdown-item" href="#1">Move</a></li>
									<li><a class="dropdown-item" href="#1">Checkout</a></li>
									<li><a class="dropdown-item" href="#1">Permissions</a></li>
									<li><a class="dropdown-item" href="#1">Move to Recycle Bin</a></li>
								</ul>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
	<div class="col-8">
		<div class="card-type-directory form-check form-check-card form-check-middle-left">
			<label class="form-check-label">
				<input class="form-check-input" type="checkbox">
				<div class="card card-horizontal">
					<div class="card-body">
						<div class="card-row">
							<div class="autofit-col">
								<span class="sticker">
									<span class="inline-item">
										<svg aria-hidden="true" class="lexicon-icon lexicon-icon-folder">
											<use xlink:href="/images/icons/icons.svg#folder" />
										</svg>
									</span>
								</span>
							</div>
							<div class="autofit-col autofit-col-expand autofit-col-gutters">
								<section class="autofit-section">
									<h3 class="card-title" title="ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual">
										<span class="text-truncate-inline">
											<span class="text-truncate">ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual</span>
										</span>
									</h3>
								</section>
							</div>
							<div class="autofit-col">
								<div class="dropdown dropdown-action">
									<a aria-expanded="false" aria-haspopup="true" class="component-action dropdown-toggle" data-toggle="dropdown" href="#1" role="button">
										<svg aria-hidden="true" class="lexicon-icon lexicon-icon-ellipsis-v">
											<use xlink:href="/images/icons/icons.svg#ellipsis-v" />
										</svg>
									</a>
									<ul class="dropdown-menu dropdown-menu-right">
										<li><a class="dropdown-item" href="#1">Download</a></li>
										<li><a class="dropdown-item" href="#1">Edit</a></li>
										<li><a class="dropdown-item" href="#1">Move</a></li>
										<li><a class="dropdown-item" href="#1">Checkout</a></li>
										<li><a class="dropdown-item" href="#1">Permissions</a></li>
										<li><a class="dropdown-item" href="#1">Move to Recycle Bin</a></li>
									</ul>
								</div>
							</div>
						</div>
					</div>
				</div>
			</label>
		</div>
	</div>
	<div class="col-4">
		<div class="card-type-asset form-check form-check-card form-check-top-left image-card">
			<div class="custom-control custom-checkbox">
				<label>
					<input class="custom-control-input" type="checkbox">
					<span class="custom-control-label"></span>
					<div class="card">
						<div class="aspect-ratio card-item-first">
							<img alt="thumbnail" class="aspect-ratio-item-center-middle aspect-ratio-item-fluid" src="/images/thumbnail_coffee.jpg">
							<span class="sticker sticker-bottom-left sticker-warning">PNG</span>
						</div>
						<div class="card-body">
							<div class="card-row">
								<div class="autofit-col autofit-col-expand">
									<section class="autofit-section">
										<h3 class="card-title">
											<span class="text-truncate-inline">
												<span class="text-truncate">Aldcott Gage George Polwarth-Kitchener</span>
											</span>
										</h3>
										<p class="card-subtitle" title="thumbnail_dock.jpg">
											<span class="text-truncate-inline">
												<a class="text-truncate" href="#1">thumbnail_dock.jpg</a>
											</span>
										</p>
										<div class="card-detail">
											<span class="label label-success">
												<span class="label-item label-item-expand">Approved</span>
											</span>
										</div>
									</section>
								</div>
								<div class="autofit-col">
									<div class="dropdown dropdown-action">
										<a aria-expanded="false" aria-haspopup="true" class="component-action dropdown-toggle" data-toggle="dropdown" href="#1" role="button">
											<svg aria-hidden="true" class="lexicon-icon lexicon-icon-ellipsis-v">
												<use xlink:href="/images/icons/icons.svg#ellipsis-v" />
											</svg>
										</a>
										<ul class="dropdown-menu dropdown-menu-right">
											<li><a class="dropdown-item" href="#1">Download</a></li>
											<li><a class="dropdown-item" href="#1">Edit</a></li>
											<li><a class="dropdown-item" href="#1">Move</a></li>
											<li><a class="dropdown-item" href="#1">Checkout</a></li>
											<li><a class="dropdown-item" href="#1">Permissions</a></li>
											<li><a class="dropdown-item" href="#1">Move to Recycle Bin</a></li>
										</ul>
									</div>
								</div>
							</div>
						</div>
					</div>
				</label>
			</div>
		</div>
	</div>
	<div class="col-8">
		<div class="card-type-directory form-check form-check-card form-check-middle-left">
			<div class="custom-control custom-checkbox">
				<label>
					<input class="custom-control-input" type="checkbox">
					<span class="custom-control-label"></span>
					<div class="card card-horizontal">
						<div class="card-body">
							<div class="card-row">
								<div class="autofit-col">
									<span class="sticker">
										<span class="inline-item">
											<svg aria-hidden="true" class="lexicon-icon lexicon-icon-folder">
												<use xlink:href="/images/icons/icons.svg#folder" />
											</svg>
										</span>
									</span>
								</div>
								<div class="autofit-col autofit-col-expand autofit-col-gutters">
									<section class="autofit-section">
										<h3 class="card-title" title="ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual">
											<span class="text-truncate-inline">
												<span class="text-truncate">ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual</span>
											</span>
										</h3>
									</section>
								</div>
								<div class="autofit-col">
									<div class="dropdown dropdown-action">
										<a aria-expanded="false" aria-haspopup="true" class="component-action dropdown-toggle" data-toggle="dropdown" href="#1" role="button">
											<svg aria-hidden="true" class="lexicon-icon lexicon-icon-ellipsis-v">
												<use xlink:href="/images/icons/icons.svg#ellipsis-v" />
											</svg>
										</a>
										<ul class="dropdown-menu dropdown-menu-right">
											<li><a class="dropdown-item" href="#1">Download</a></li>
											<li><a class="dropdown-item" href="#1">Edit</a></li>
											<li><a class="dropdown-item" href="#1">Move</a></li>
											<li><a class="dropdown-item" href="#1">Checkout</a></li>
											<li><a class="dropdown-item" href="#1">Permissions</a></li>
											<li><a class="dropdown-item" href="#1">Move to Recycle Bin</a></li>
										</ul>
									</div>
								</div>
							</div>
						</div>
					</div>
				</label>
			</div>
		</div>
	</div>
</div>

```html
<div class="form-check form-check-card form-check-top-left">
    <label class="form-check-label">
        <input class="form-check-input" type="checkbox">
        <div class="card">...</div>
    </label>
</div>
```

</article>

<article>

### Clickable Radio Card

<p>To make the whole card clickable just wrap the radio input and card in:</p>

<div class="row">
	<div class="col-4">
		<div class="card-type-asset form-check form-check-card form-check-top-left image-card">
			<label class="form-check-label">
				<input class="form-check-input" name="cardRadios" type="radio" value="cardOption1">
				<div class="card">
					<div class="aspect-ratio card-item-first">
						<img alt="thumbnail" class="aspect-ratio-item-center-middle aspect-ratio-item-fluid" src="/images/thumbnail_coffee.jpg">
						<span class="sticker sticker-bottom-left sticker-warning">PNG</span>
					</div>
					<div class="card-body">
						<div class="card-row">
							<div class="autofit-col autofit-col-expand">
								<section class="autofit-section">
									<h3 class="card-title">
										<span class="text-truncate-inline">
											<span class="text-truncate">Aldcott Gage George Polwarth-Kitchener</span>
										</span>
									</h3>
									<p class="card-subtitle" title="thumbnail_dock.jpg">
										<span class="text-truncate-inline">
											<a class="text-truncate" href="#1">thumbnail_dock.jpg</a>
										</span>
									</p>
									<div class="card-detail">
										<span class="label label-success">
											<span class="label-item label-item-expand">Approved</span>
										</span>
									</div>
								</section>
							</div>
							<div class="autofit-col">
								<div class="dropdown dropdown-action">
									<a aria-expanded="false" aria-haspopup="true" class="component-action dropdown-toggle" data-toggle="dropdown" href="#1" role="button">
										<svg aria-hidden="true" class="lexicon-icon lexicon-icon-ellipsis-v">
											<use xlink:href="/images/icons/icons.svg#ellipsis-v" />
										</svg>
									</a>
									<ul class="dropdown-menu dropdown-menu-right">
										<li><a class="dropdown-item" href="#1">Download</a></li>
										<li><a class="dropdown-item" href="#1">Edit</a></li>
										<li><a class="dropdown-item" href="#1">Move</a></li>
										<li><a class="dropdown-item" href="#1">Checkout</a></li>
										<li><a class="dropdown-item" href="#1">Permissions</a></li>
										<li><a class="dropdown-item" href="#1">Move to Recycle Bin</a></li>
									</ul>
								</div>
							</div>
						</div>
					</div>
				</div>
			</label>
		</div>
	</div>
	<div class="col-8">
		<div class="card-type-directory form-check form-check-card form-check-middle-left">
			<label class="form-check-label">
				<input class="form-check-input" name="cardRadios" type="radio" value="cardOption2">
				<div class="card card-horizontal">
					<div class="card-body">
						<div class="card-row">
							<div class="autofit-col">
								<span class="sticker">
									<span class="inline-item">
										<svg aria-hidden="true" class="lexicon-icon lexicon-icon-folder">
											<use xlink:href="/images/icons/icons.svg#folder" />
										</svg>
									</span>
								</span>
							</div>
							<div class="autofit-col autofit-col-expand autofit-col-gutters">
								<section class="autofit-section">
									<h3 class="card-title" title="ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual">
										<span class="text-truncate-inline">
											<span class="text-truncate">ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual</span>
										</span>
									</h3>
								</section>
							</div>
							<div class="autofit-col">
								<div class="dropdown dropdown-action">
									<a aria-expanded="false" aria-haspopup="true" class="component-action dropdown-toggle" data-toggle="dropdown" href="#1" role="button">
										<svg aria-hidden="true" class="lexicon-icon lexicon-icon-ellipsis-v">
											<use xlink:href="/images/icons/icons.svg#ellipsis-v" />
										</svg>
									</a>
									<ul class="dropdown-menu dropdown-menu-right">
										<li><a class="dropdown-item" href="#1">Download</a></li>
										<li><a class="dropdown-item" href="#1">Edit</a></li>
										<li><a class="dropdown-item" href="#1">Move</a></li>
										<li><a class="dropdown-item" href="#1">Checkout</a></li>
										<li><a class="dropdown-item" href="#1">Permissions</a></li>
										<li><a class="dropdown-item" href="#1">Move to Recycle Bin</a></li>
									</ul>
								</div>
							</div>
						</div>
					</div>
				</div>
			</label>
		</div>
	</div>
	<div class="col-4">
		<div class="card-type-asset form-check form-check-card form-check-top-left image-card">
			<div class="custom-control custom-radio">
				<label>
					<input class="custom-control-input" name="cardCustomRadios" type="radio" value="cardCustomRadioOption1">
					<span class="custom-control-label"></span>
					<div class="card">
						<div class="aspect-ratio card-item-first">
							<img alt="thumbnail" class="aspect-ratio-item-center-middle aspect-ratio-item-fluid" src="/images/thumbnail_coffee.jpg">
							<span class="sticker sticker-bottom-left sticker-warning">PNG</span>
						</div>
						<div class="card-body">
							<div class="card-row">
								<div class="autofit-col autofit-col-expand">
									<section class="autofit-section">
										<h3 class="card-title">
											<span class="text-truncate-inline">
												<span class="text-truncate">Aldcott Gage George Polwarth-Kitchener</span>
											</span>
										</h3>
										<p class="card-subtitle" title="thumbnail_dock.jpg">
											<span class="text-truncate-inline">
												<a class="text-truncate" href="#1">thumbnail_dock.jpg</a>
											</span>
										</p>
										<div class="card-detail">
											<span class="label label-success">
												<span class="label-item label-item-expand">Approved</span>
											</span>
										</div>
									</section>
								</div>
								<div class="autofit-col">
									<div class="dropdown dropdown-action">
										<a aria-expanded="false" aria-haspopup="true" class="component-action dropdown-toggle" data-toggle="dropdown" href="#1" role="button">
											<svg aria-hidden="true" class="lexicon-icon lexicon-icon-ellipsis-v">
												<use xlink:href="/images/icons/icons.svg#ellipsis-v" />
											</svg>
										</a>
										<ul class="dropdown-menu dropdown-menu-right">
											<li><a class="dropdown-item" href="#1">Download</a></li>
											<li><a class="dropdown-item" href="#1">Edit</a></li>
											<li><a class="dropdown-item" href="#1">Move</a></li>
											<li><a class="dropdown-item" href="#1">Checkout</a></li>
											<li><a class="dropdown-item" href="#1">Permissions</a></li>
											<li><a class="dropdown-item" href="#1">Move to Recycle Bin</a></li>
										</ul>
									</div>
								</div>
							</div>
						</div>
					</div>
				</label>
			</div>
		</div>
	</div>
	<div class="col-8">
		<div class="card-type-directory form-check form-check-card form-check-middle-left">
			<div class="custom-control custom-radio">
				<label>
					<input class="custom-control-input" name="cardCustomRadios" type="radio" value="cardCustomRadioOption2">
					<span class="custom-control-label"></span>
					<div class="card card-horizontal">
						<div class="card-body">
							<div class="card-row">
								<div class="autofit-col">
									<span class="sticker">
										<span class="inline-item">
											<svg aria-hidden="true" class="lexicon-icon lexicon-icon-folder">
												<use xlink:href="/images/icons/icons.svg#folder" />
											</svg>
										</span>
									</span>
								</div>
								<div class="autofit-col autofit-col-expand autofit-col-gutters">
									<section class="autofit-section">
										<h3 class="card-title" title="ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual">
											<span class="text-truncate-inline">
												<span class="text-truncate">ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual</span>
											</span>
										</h3>
									</section>
								</div>
								<div class="autofit-col">
									<div class="dropdown dropdown-action">
										<a aria-expanded="false" aria-haspopup="true" class="component-action dropdown-toggle" data-toggle="dropdown" href="#1" role="button">
											<svg aria-hidden="true" class="lexicon-icon lexicon-icon-ellipsis-v">
												<use xlink:href="/images/icons/icons.svg#ellipsis-v" />
											</svg>
										</a>
										<ul class="dropdown-menu dropdown-menu-right">
											<li><a class="dropdown-item" href="#1">Download</a></li>
											<li><a class="dropdown-item" href="#1">Edit</a></li>
											<li><a class="dropdown-item" href="#1">Move</a></li>
											<li><a class="dropdown-item" href="#1">Checkout</a></li>
											<li><a class="dropdown-item" href="#1">Permissions</a></li>
											<li><a class="dropdown-item" href="#1">Move to Recycle Bin</a></li>
										</ul>
									</div>
								</div>
							</div>
						</div>
					</div>
				</label>
			</div>
		</div>
	</div>
</div>

```html
<div class="form-check form-check-card form-check-top-left">
    <label class="form-check-label">
        <input class="form-check-input" type="radio">
        <div class="card">...</div>
    </label>
</div>
```

</article>

<article>

### Checkbox Card

<p>We have created a pattern to add checkboxes to cards, just wrap the checkbox and card in:</p>

<div class="alert alert-warning">
	Requires javascript to add and remove the <code>active</code> class when the input is checked/unchecked.
</div>

<div class="row">
	<div class="col-4">
		<div class="active card-type-asset form-check form-check-card form-check-top-left image-card">
			<label class="form-check-label">
				<input checked class="form-check-input" type="checkbox">
			</label>
			<div class="card">
				<div class="aspect-ratio card-item-first">
					<img alt="thumbnail" class="aspect-ratio-item-center-middle aspect-ratio-item-fluid" src="/images/thumbnail_coffee.jpg">
					<span class="sticker sticker-bottom-left sticker-warning">PNG</span>
				</div>
				<div class="card-body">
					<div class="card-row">
						<div class="autofit-col autofit-col-expand">
							<section class="autofit-section">
								<h3 class="card-title">
									<span class="text-truncate-inline">
										<span class="text-truncate">Aldcott Gage George Polwarth-Kitchener</span>
									</span>
								</h3>
								<p class="card-subtitle" title="thumbnail_dock.jpg">
									<span class="text-truncate-inline">
										<span class="text-truncate">thumbnail_dock.jpg</span>
									</span>
								</p>
								<div class="card-detail">
									<span class="label label-success">
										<span class="label-item label-item-expand">Approved</span>
									</span>
								</div>
							</section>
						</div>
						<div class="autofit-col">
							<div class="dropdown dropdown-action">
								<a aria-expanded="false" aria-haspopup="true" class="component-action dropdown-toggle" data-toggle="dropdown" href="#1" role="button">
									<svg aria-hidden="true" class="lexicon-icon lexicon-icon-ellipsis-v">
										<use xlink:href="/images/icons/icons.svg#ellipsis-v" />
									</svg>
								</a>
								<ul class="dropdown-menu dropdown-menu-right">
									<li><a class="dropdown-item" href="#1">Download</a></li>
									<li><a class="dropdown-item" href="#1">Edit</a></li>
									<li><a class="dropdown-item" href="#1">Move</a></li>
									<li><a class="dropdown-item" href="#1">Checkout</a></li>
									<li><a class="dropdown-item" href="#1">Permissions</a></li>
									<li><a class="dropdown-item" href="#1">Move to Recycle Bin</a></li>
								</ul>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
	<div class="col-8">
		<div class="card-type-directory form-check form-check-card form-check-middle-left">
			<label class="form-check-label">
				<input class="form-check-input" type="checkbox">
			</label>
			<div class="card card-horizontal">
				<div class="card-body">
					<div class="card-row">
						<div class="autofit-col">
							<span class="sticker">
								<span class="inline-item">
									<svg aria-hidden="true" class="lexicon-icon lexicon-icon-folder">
										<use xlink:href="/images/icons/icons.svg#folder" />
									</svg>
								</span>
							</span>
						</div>
						<div class="autofit-col autofit-col-expand autofit-col-gutters">
							<section class="autofit-section">
								<h3 class="card-title" title="ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual">
									<span class="text-truncate-inline">
										<span class="text-truncate">ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual</span>
									</span>
								</h3>
							</section>
						</div>
						<div class="autofit-col">
							<div class="dropdown dropdown-action">
								<a aria-expanded="false" aria-haspopup="true" class="component-action dropdown-toggle" data-toggle="dropdown" href="#1" role="button">
									<svg aria-hidden="true" class="lexicon-icon lexicon-icon-ellipsis-v">
										<use xlink:href="/images/icons/icons.svg#ellipsis-v" />
									</svg>
								</a>
								<ul class="dropdown-menu dropdown-menu-right">
									<li><a class="dropdown-item" href="#1">Download</a></li>
									<li><a class="dropdown-item" href="#1">Edit</a></li>
									<li><a class="dropdown-item" href="#1">Move</a></li>
									<li><a class="dropdown-item" href="#1">Checkout</a></li>
									<li><a class="dropdown-item" href="#1">Permissions</a></li>
									<li><a class="dropdown-item" href="#1">Move to Recycle Bin</a></li>
								</ul>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="card-type-directory form-check form-check-card form-check-middle-left">
			<div class="custom-control custom-checkbox">
				<label>
					<input class="custom-control-input" type="checkbox">
					<span class="custom-control-label"></span>
				</label>
			</div>
			<div class="card card-horizontal">
				<div class="card-body">
					<div class="card-row">
						<div class="autofit-col">
							<span class="sticker">
								<span class="inline-item">
									<svg aria-hidden="true" class="lexicon-icon lexicon-icon-folder">
										<use xlink:href="/images/icons/icons.svg#folder" />
									</svg>
								</span>
							</span>
						</div>
						<div class="autofit-col autofit-col-expand autofit-col-gutters">
							<section class="autofit-section">
								<h3 class="card-title" title="ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual">
									<span class="text-truncate-inline">
										<span class="text-truncate">ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual</span>
									</span>
								</h3>
							</section>
						</div>
						<div class="autofit-col">
							<div class="dropdown dropdown-action">
								<a aria-expanded="false" aria-haspopup="true" class="component-action dropdown-toggle" data-toggle="dropdown" href="#1" role="button">
									<svg aria-hidden="true" class="lexicon-icon lexicon-icon-ellipsis-v">
										<use xlink:href="/images/icons/icons.svg#ellipsis-v" />
									</svg>
								</a>
								<ul class="dropdown-menu dropdown-menu-right">
									<li><a class="dropdown-item" href="#1">Download</a></li>
									<li><a class="dropdown-item" href="#1">Edit</a></li>
									<li><a class="dropdown-item" href="#1">Move</a></li>
									<li><a class="dropdown-item" href="#1">Checkout</a></li>
									<li><a class="dropdown-item" href="#1">Permissions</a></li>
									<li><a class="dropdown-item" href="#1">Move to Recycle Bin</a></li>
								</ul>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</div>

```html
<div class="form-check form-check-card form-check-top-left">
    <label class="form-check-label">
        <input class="form-check-input" type="checkbox">
    </label>
    <div class="card">...</div>
</div>
```

</article>

<article>

### Radio Card

<p>We have created a pattern to add radio inputs to cards, just wrap the radio input and card in:</p>

<div class="alert alert-warning">
	Requires javascript to add and remove the <code>active</code> class when the input is checked/unchecked.
</div>

<div class="row">
	<div class="col-4">
		<div class="active card-type-asset form-check form-check-card form-check-top-left image-card">
			<label class="form-check-label">
				<input checked class="form-check-input" name="cardRadios1" type="radio" value="cardOption1">
			</label>
			<div class="card">
				<div class="aspect-ratio card-item-first">
					<img alt="thumbnail" class="aspect-ratio-item-center-middle aspect-ratio-item-fluid" src="/images/thumbnail_coffee.jpg">
					<span class="sticker sticker-bottom-left sticker-warning">PNG</span>
				</div>
				<div class="card-body">
					<div class="card-row">
						<div class="autofit-col autofit-col-expand">
							<section class="autofit-section">
								<h3 class="card-title">
									<span class="text-truncate-inline">
										<span class="text-truncate">Aldcott Gage George Polwarth-Kitchener</span>
									</span>
								</h3>
								<p class="card-subtitle" title="thumbnail_dock.jpg">
									<span class="text-truncate-inline">
										<a class="text-truncate" href="#1">thumbnail_dock.jpg</a>
									</span>
								</p>
								<div class="card-detail">
									<span class="label label-success">
										<span class="label-item label-item-expand">Approved</span>
									</span>
								</div>
							</section>
						</div>
						<div class="autofit-col">
							<div class="dropdown dropdown-action">
								<a aria-expanded="false" aria-haspopup="true" class="component-action dropdown-toggle" data-toggle="dropdown" href="#1" role="button">
									<svg aria-hidden="true" class="lexicon-icon lexicon-icon-ellipsis-v">
										<use xlink:href="/images/icons/icons.svg#ellipsis-v" />
									</svg>
								</a>
								<ul class="dropdown-menu dropdown-menu-right">
									<li><a class="dropdown-item" href="#1">Download</a></li>
									<li><a class="dropdown-item" href="#1">Edit</a></li>
									<li><a class="dropdown-item" href="#1">Move</a></li>
									<li><a class="dropdown-item" href="#1">Checkout</a></li>
									<li><a class="dropdown-item" href="#1">Permissions</a></li>
									<li><a class="dropdown-item" href="#1">Move to Recycle Bin</a></li>
								</ul>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
	<div class="col-8">
		<div class="card-type-directory form-check form-check-card form-check-middle-left">
			<label class="form-check-label">
				<input class="form-check-input" name="cardRadios1" type="radio" value="cardOption2">
			</label>
			<div class="card card-horizontal">
				<div class="card-body">
					<div class="card-row">
						<div class="autofit-col">
							<span class="sticker">
								<span class="inline-item">
									<svg aria-hidden="true" class="lexicon-icon lexicon-icon-folder">
										<use xlink:href="/images/icons/icons.svg#folder" />
									</svg>
								</span>
							</span>
						</div>
						<div class="autofit-col autofit-col-expand autofit-col-gutters">
							<section class="autofit-section">
								<h3 class="card-title" title="ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual">
									<span class="text-truncate-inline">
										<span class="text-truncate">ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual</span>
									</span>
								</h3>
							</section>
						</div>
						<div class="autofit-col">
							<div class="dropdown dropdown-action">
								<a aria-expanded="false" aria-haspopup="true" class="component-action dropdown-toggle" data-toggle="dropdown" href="#1" role="button">
									<svg aria-hidden="true" class="lexicon-icon lexicon-icon-ellipsis-v">
										<use xlink:href="/images/icons/icons.svg#ellipsis-v" />
									</svg>
								</a>
								<ul class="dropdown-menu dropdown-menu-right">
									<li><a class="dropdown-item" href="#1">Download</a></li>
									<li><a class="dropdown-item" href="#1">Edit</a></li>
									<li><a class="dropdown-item" href="#1">Move</a></li>
									<li><a class="dropdown-item" href="#1">Checkout</a></li>
									<li><a class="dropdown-item" href="#1">Permissions</a></li>
									<li><a class="dropdown-item" href="#1">Move to Recycle Bin</a></li>
								</ul>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="card-type-directory form-check form-check-card form-check-middle-left">
			<div class="custom-control custom-radio">
				<label>
					<input class="custom-control-input" name="cardRadios1" type="radio" value="cardOption3">
					<span class="custom-control-label"></span>
				</label>
			</div>
			<div class="card card-horizontal">
				<div class="card-body">
					<div class="card-row">
						<div class="autofit-col">
							<span class="sticker">
								<span class="inline-item">
									<svg aria-hidden="true" class="lexicon-icon lexicon-icon-folder">
										<use xlink:href="/images/icons/icons.svg#folder" />
									</svg>
								</span>
							</span>
						</div>
						<div class="autofit-col autofit-col-expand autofit-col-gutters">
							<section class="autofit-section">
								<h3 class="card-title" title="ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual">
									<span class="text-truncate-inline">
										<span class="text-truncate">ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual</span>
									</span>
								</h3>
							</section>
						</div>
						<div class="autofit-col">
							<div class="dropdown dropdown-action">
								<a aria-expanded="false" aria-haspopup="true" class="component-action dropdown-toggle" data-toggle="dropdown" href="#1" role="button">
									<svg aria-hidden="true" class="lexicon-icon lexicon-icon-ellipsis-v">
										<use xlink:href="/images/icons/icons.svg#ellipsis-v" />
									</svg>
								</a>
								<ul class="dropdown-menu dropdown-menu-right">
									<li><a class="dropdown-item" href="#1">Download</a></li>
									<li><a class="dropdown-item" href="#1">Edit</a></li>
									<li><a class="dropdown-item" href="#1">Move</a></li>
									<li><a class="dropdown-item" href="#1">Checkout</a></li>
									<li><a class="dropdown-item" href="#1">Permissions</a></li>
									<li><a class="dropdown-item" href="#1">Move to Recycle Bin</a></li>
								</ul>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</div>

```html
<div class="form-check form-check-card form-check-top-left">
    <label class="form-check-label">
        <input class="form-check-input" type="radio">
    </label>
    <div class="card">...</div>
</div>
```

</article>