lib  
│  
├── models  
│   ├── comment.dart
│   ├── notification.dart  
│   └── post.dart  
│  
├── providers  
│   ├── firebase.dart  
│   ├── comments.dart  
│   ├── notifications.dart  
│   └── posts.dart                        -- firebase에 들어갈 데이터 구조  
│  
├── screens  
│   ├── login_screen.dart  
│   ├── community_screen.dart                  -- 게시글 목록 메인 화면  
│   ├── write_screen.dart              -- 글 작성 화면  
│   ├── notification_screen.dart  
│   ├── post_detail_screen.dart            -- 게시글 상세 화면 + 댓글  
│   ├── search_screen.dart  
│   └── splash_screen.dart  
│  
├── widgets  
│   ├── app_drawer.dart                   -- 화면 좌측 탭_drawBar  
│   ├── comment_item.dart  
│   ├── notification_item.dart  
│   └── post_item.dart                    -- 게시글 목록에 출력되는 타일 내용 위젯  
│  
└── main.dart  
