# BOTMAN
when i used this $botman->hears('give me videos', function($bot){     $video = Video::url('http://laracon.dev/video/botman.mp4');     $message = OutgoingMessage::create()->withAttachment($video);     $bot->reply($message); }); i got 500 internal server error
