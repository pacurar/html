====<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="http://code.jquery.com/mobile/1.4.4/jquery.mobile-1.4.4.min.css">
<script src="http://code.jquery.com/jquery-1.11.1.min.js"></script>
<script src="http://code.jquery.com/mobile/1.4.4/jquery.mobile-1.4.4.min.js"></script>
</head>
<body>

<div data-role="pageone">
  <div data-role="header">
    <h1>Welcome To My Homepage</h1>
  </div>

  <div data-role="main" class="ui-content">
    <p>Click on the image to enlarge it.</p>
    <p>Notice that we have added a "back button" in the top right corner.</p>
    <a href="#myPopup" data-rel="popup" data-position-to="window">
    <img src="skaret.jpg" alt="Skaret View" style="width:200px;"></a>

    <div data-role="popup" id="myPopup">
      <p>This is my picture!</p> 
      <a href="#" data-rel="back" class="ui-btn ui-corner-all ui-shadow ui-btn-a ui-icon-delete ui-btn-icon-notext ui-btn-right">Close</a><img src="skaret.jpg" style="width:800px;height:500px;" alt="Skaret View">
    </div>
  </div>

  <div data-role="footer">
    <h1>Footer Text</h1>
  </div>
</div> 
<div data-role="pagetwo">
  <div data-role="header">
    <h1>Welcome To My Homepage</h1>
  </div>

  <div data-role="main" class="ui-content">
    <p>Click on the image to enlarge it.</p>
    <p>Notice that we have added a "back button" in the top right corner.</p>
    <a href="#myPopup" data-rel="popup" data-position-to="window">
    <img src="skaret.jpg" alt="Skaret View" style="width:200px;"></a>

    <div data-role="popup" id="myPopup">
      <p>This is my picture!</p> 
      <a href="#" data-rel="back" class="ui-btn ui-corner-all ui-shadow ui-btn-a ui-icon-delete ui-btn-icon-notext ui-btn-right">Close</a><img src="skaret.jpg" style="width:800px;height:500px;" alt="Skaret View">
    </div>
  </div>

  <div data-role="footer">
    <h1>Footer Text</h1>
  </div>
</div>

</body>
</html>

