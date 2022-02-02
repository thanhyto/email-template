<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.5.0/font/bootstrap-icons.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="thanh-to-email-template.css">
    
    <title>Thanh's Email</title>
</head>
<body>
    <div class="container-fluid">
        <div class="row">
            <div class="col-md-2 my-col-left">
                <div class="text-center">
                    <h6 class="mt-4"><img src="https://ddragon.leagueoflegends.com/cdn/11.1.1/img/profileicon/3587.png" class="rounded-circle" width=50px> Hello, Thanh!</h6>                
                
                    <button type="button" class="btn btn-outline-primary btn-lg mt-2 mb-2"><i class="fa fa-plus"></i> Compose Mail</button>
                </div>
                <ul class="list-unstyled mt-2">Folders
                <li class="active"><i class="bi bi-inbox-fill"></i>&nbsp;&nbsp;Inbox<span class="pull-right">3</span></li>
                <li><i class="bi bi-journal"></i>&nbsp;&nbsp;Drafts</li>
                <li><i class="bi bi-folder-symlink"></i>&nbsp;&nbsp;Sent</li>
                <li><i class="bi bi-folder"></i>&nbsp;&nbsp;Spam</li>
                <li><i class="bi bi-trash"></i>&nbsp;&nbsp;Trash</li>
                <li><i class="bi bi-star"></i>&nbsp;&nbsp;Starred</li>
                </ul>
            </div>
            <div class="col-md-4 my-col-center">
                <form>
                <div class="input-group mt-4">
                    <button type="button" class="input-group-addon btn"><i class="fa fa-search"></i></button>
                    <input type="text" class="form-control" id="search" placeholder="Search">
                </div> 
                </form>
                <div class="card mt-4">
                    <div class="card-body">
                        <h5 class="card-title">Linkedln<span class="pull-right" id="time">3:00pm</span></h5>
                        <p class="card-text">You have a new connection request</p>
                        <i class="email bi bi-paperclip"></i>
                        <i class="email bi bi-star"></i>
                        <i class="email bi bi-trash"></i>
                        <i class="email bi bi-three-dots-vertical"></i>
                    </div>
                </div>
                <div class="card my-card-active mt-4">
                    <div class="card-body">
                        <h5 class="card-title">Netflix<span class="pull-right" id="time">May 1, 2021</span></h5>
                        <p class="card-text">Thanh, here's what coming soon to Netflix</p>
                        <i class="email bi bi-paperclip"></i>
                        <i class="email bi bi-star"></i>
                        <i class="email bi bi-trash"></i>
                        <i class="email bi bi-three-dots-vertical"></i>
                    </div>
                </div>
                <div class="card mt-4">
                    <div class="card-body">
                        <h5 class="card-title">Reddit<span class="pull-right" id="time">Jan 3, 2021</span></h5>
                        <p class="card-text">u/nakulane replied to your comment in...</p>
                        <i class="email bi bi-paperclip"></i>
                        <i class="email bi bi-star"></i>
                        <i class="email bi bi-trash"></i>
                        <i class="email bi bi-three-dots-vertical"></i>
                    </div>
                </div>
            </div>
            <div class="col-md-6 my-col-right">
                <p class="address mt-4">From: Netflix netflix_info@mailer.netflix.com</p>
                <span class="pull-right icon">
                    <i class="email bi bi-paperclip"></i>
                    <i class="email bi bi-star"></i>
                    <i class="email bi bi-trash"></i>
                    <i class="email bi bi-three-dots-vertical"></i>
                </span>
                <h2 class="mt-2">Thanh, here's what coming soon to Netflix</h2>
                <p class="mt-5">Hi Thanh,</p>
                <p class="mb-5">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Enim nam voluptatibus magni excepturi ipsam quam, eum dicta. Quaerat ut accusantium omnis vero asperiores sunt culpa. Necessitatibus atque provident, recusandae voluptatibus quasi sit sapiente assumenda in facilis. Dignissimos odio ipsum, rerum consequuntur modi magni, et vitae ipsam beatae repudiandae reiciendis esse.</p>
                <textarea class="border-3 rounded mt-5" rows="10" placeholder="Write a reply..."></textarea>
                <button type="button" class="btn btn-primary btn-lg pull-right">Send</button>
            </div>
        </div>
    </div>
</body>
</html>
