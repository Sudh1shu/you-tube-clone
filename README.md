<!DOCTYPE html>
<html lang="eng">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>YouTube Home Page Clone</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }

        .header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            background-color: #b41111;
            color: black;
            padding: 10px 20px;
        }

        .header .logo {
            font-size: 24px;
            font-weight: bold;
        }

        .header .search {
            display: flex;
            align-items: center;
            flex:1;
            margin: 0 20px;
        }

        .header .search input {
            width: 100%;
            padding: 8px;
            border: none;
            border-radius: 2px;
        }

        .header .search button {
            padding: 8px 12px;
            background-color: rgba(31, 28, 28, 0.341);
            border: none;
            border-left: 1px solid #ebd2d2;
            cursor: pointer;
        }

        .header .search button:hover {
            background-color: #f2f2f2;
        }

        .header .user {
            font-size: 16px;
            cursor: pointer;
        }

        .sidebar {
            width: 200px;
            background-color: #efebeb;
            height: 100vh;
            padding: 20px;
            box-shadow: 2px 0 5px rgba(0, 0, 0, 0.1);
            position: fixed;
            top: 0;
            left: 0;
        }

        .sidebar ul {
            list-style: none;
            padding: 0;
        }

        .sidebar ul li {
            padding: 10px 0;
            cursor: pointer;
        }

        .sidebar ul li:hover {
            background-color: #5e3636;
        }

        .content {
            margin-left: 220px;
            padding: 20px;
        }

        .content .video {
            display: inline-block;
            width: 30%;
            margin: 1%;
            background-color: #fff;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
            overflow: hidden;
        }

        .content .video img {
            width: 100%;
            display: block;
        }

        .content .video .info {
            padding: 10px;
        }

        .content .video .info h3 {
            font-size: 16px;
            margin: 0;
            color: #333;
        }

        .content .video .info p {
            font-size: 14px;
            color: #666;
        }
    </style>
</head>
<body>

<!-- Header -->
<div class="header">
    <div class="logo">YouTube</div>
    <div class="search">
        <input type="text" placeholder="Search">
        <button>Search</button>
    </div>
    <div class="user">User Icon</div>
</div>

<!-- Sidebar -->
<div class="sidebar">
    <ul>
        <li>Home</li>
        <li>Trending</li>
        <li>Subscriptions</li>
        <li>Library</li>
        <li>History</li>
        <li>podcast</li>
        <li>music</li>
    </ul>
</div>

<!-- Main Content -->
<div class="content">
    <div class="video">
        <img src="https://via.placeholder.com/300x180" alt="Video Thumbnail">
        <div class="info">
            <h3>Video Title 1</h3>
            <p>apnacollege</p>
        </div>
    </div>

    <div class="video">
        <img src="https://via.placeholder.com/300x180" alt="Video Thumbnail">
        <div class="info">
            <h3>Video Title 2</h3>
            <p><t-series></p>
        </div>
    </div>

    <div class="video">
        <img src="https://via.placeholder.com/300x180" alt="Video Thumbnail">
        <div class="info">
            <h3>Video Title 3</h3>
            <p>codewithharry</p>
        </div>
    </div>
</div>

</body>
</html>
