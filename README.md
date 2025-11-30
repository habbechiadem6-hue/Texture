<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SmartFinder - Find the Best Products Instantly</title>
  <style>
    body { font-family: Arial, sans-serif; margin:0; padding:0; background:#f5f5f5; }
    header { background:#000; color:#fff; padding:20px; text-align:center; font-size:28px; font-weight:bold; }
    .container { width:90%; max-width:900px; margin:40px auto; }
    .search-box { background:#fff; padding:30px; border-radius:12px; box-shadow:0 4px 12px rgba(0,0,0,0.1); }
    .search-box h2 { margin-top:0; font-size:24px; }
    input[type="text"] { width:100%; padding:15px; border-radius:10px; border:1px solid #ccc; font-size:16px; }
    button { margin-top:20px; padding:15px 25px; background:#000; color:#fff; border:none; border-radius:10px; font-size:18px; cursor:pointer; }
    .section-title { margin-top:50px; font-size:24px; font-weight:bold; }
    .list-card { background:#fff; padding:20px; margin-top:15px; border-radius:10px; box-shadow:0 4px 10px rgba(0,0,0,0.08); }
    .list-card h3 { margin:0; }
  </style>
</head>
<body>
  <header>SmartFinder</header>

  <div class="container">
    <div class="search-box">
      <h2>Find the Best Product Instantly</h2>
      <p>Type what you're searching for (e.g. "best phone under $300", "best wireless earbuds 2025")</p>
      <input type="text" placeholder="Search for any product..." />
      <button>Search</button>
    </div>

    <h2 class="section-title">Top Categories</h2>

    <div class="list-card">
      <h3>Best Smartphones 2025</h3>
      <p>Updated global ranking of the most powerful phones.</p>
    </div>

    <div class="list-card">
      <h3>Best Laptops for Students</h3>
      <p>Affordable and powerful laptops for study and productivity.</p>
    </div>

    <div class="list-card">
      <h3>Best Budget Earbuds</h3>
      <p>Top earbuds with amazing sound quality for low prices.</p>
    </div>

    <div class="list-card">
      <h3>Best Gaming Accessories</h3>
      <p>Keyboards, mice, headsets and more for professional gamers.</p>
    </div>

  </div>
</body>
</html>
## Coming from AsyncDisplayKit? Learn more [here](https://medium.com/@Pinterest_Engineering/introducing-texture-a-new-home-for-asyncdisplaykit-e7c003308f50)

![Texture](https://github.com/texturegroup/texture/raw/master/docs/static/images/logo.png)

[![Apps Using](https://img.shields.io/cocoapods/at/Texture.svg?label=Apps%20Using%20Texture&colorB=28B9FE)](http://cocoapods.org/pods/Texture)
[![Downloads](https://img.shields.io/cocoapods/dt/Texture.svg?label=Total%20Downloads&colorB=28B9FE)](http://cocoapods.org/pods/Texture)

[![Platform](https://img.shields.io/badge/platforms-iOS%20%7C%20tvOS-orange.svg)](http://texturegroup.org)
[![Languages](https://img.shields.io/badge/languages-ObjC%20%7C%20Swift-orange.svg)](http://texturegroup.org)

[![Version](https://img.shields.io/cocoapods/v/Texture.svg)](http://cocoapods.org/pods/Texture)
[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-59C939.svg?style=flat)](https://github.com/Carthage/Carthage)
[![License](https://img.shields.io/cocoapods/l/Texture.svg)](https://github.com/texturegroup/texture/blob/master/LICENSE)

## Installation

Texture is available via CocoaPods or Carthage. See our [Installation](http://texturegroup.org/docs/installation.html) guide for instructions.

## Performance Gains

Texture's basic unit is the `node`. An ASDisplayNode is an abstraction over `UIView`, which in turn is an abstraction over `CALayer`. Unlike views, which can only be used on the main thread, nodes are thread-safe: you can instantiate and configure entire hierarchies of them in parallel on background threads.

To keep its user interface smooth and responsive, your app should render at 60 frames per second — the gold standard on iOS. This means the main thread has one-sixtieth of a second to push each frame. That's 16 milliseconds to execute all layout and drawing code! And because of system overhead, your code usually has less than ten milliseconds to run before it causes a frame drop.

Texture lets you move image decoding, text sizing and rendering, layout, and other expensive UI operations off the main thread, to keep the main thread available to respond to user interaction.

## Advanced Developer Features

As the framework has grown, many features have been added that can save developers tons of time by eliminating common boilerplate style structures common in modern iOS apps. If you've ever dealt with cell reuse bugs, tried to performantly preload data for a page or scroll style interface or even just tried to keep your app from dropping too many frames you can benefit from integrating Texture.

## Learn More

* Read the our [Getting Started](http://texturegroup.org/docs/getting-started.html) guide
* Get the [sample projects](https://github.com/texturegroup/texture/tree/master/examples)
* Browse the [API reference](http://texturegroup.org/appledocs.html)

## Getting Help

We use Slack for real-time debugging, community updates, and general talk about Texture. [Signup](https://asdk-slack-auto-invite.herokuapp.com) yourself or email textureframework@gmail.com to get an invite.

## Release process

For the release process see the [RELEASE](https://github.com/texturegroup/texture/blob/master/RELEASE.md) file.

## Contributing

We welcome any contributions. See the [CONTRIBUTING](https://github.com/texturegroup/texture/blob/master/CONTRIBUTING.md) file for how to get involved.

## License

The Texture project is available for free use, as described by the [LICENSE](https://github.com/texturegroup/texture/blob/master/LICENSE) (Apache 2.0).
