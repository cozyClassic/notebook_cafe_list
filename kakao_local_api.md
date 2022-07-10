
### 1. 카카오맵 장소 리스트

1. url : https://dapi.kakao.com/v2/local/search/keyword?query=윙스터디&page=1&size=10&analyze_type=true

2. HEADER에 카카오 개발자 포럼에서 제공하는 REST key 필요함.

3. 결과값 (간추린게 이정도)

```JSON
{
    "isMapUser": false,
    "isExist": true,
    "basicInfo": {
        "cid": 1041596354,
        "placenamefull": "윙스터디 신촌스터디룸",
        "mainphotourl": "http://t1.kakaocdn.net/mystore/61F07A40BE6142D9BED6B4D418A925A8",
        "phonenum": "02-2135-3196",
        "address": {
            "newaddr": {
                "newaddrfull": "연세로5다길 14",
                "bsizonno": "03789"
            },
            "region": {
                "name3": "창천동",
                "fullname": "서울 서대문구 창천동",
                "newaddrfullname": "서울 서대문구"
            },
            "addrbunho": "62-59",
            "addrdetail": "지하 1층"
        },
        "homepage": "https://booking.naver.com/booking/10/bizes/248159",
        "homepagenoprotocol": "booking.naver.com/booking/10/bizes/248159",
        "introduction": "아메리카노, 카페라떼 무제한 무료 제공 / 2인실부터 8인실까지 20개의 스터디룸 완비",
        "wpointx": 485591,
        "wpointy": 1126971,
        "roadview": {
            "panoid": 1139863396,
            "tilt": 0,
            "pan": 9.0,
            "wphotox": 485585,
            "wphotoy": 1126936,
            "rvlevel": 0
        },
        "category": {
            "cateid": "23758",
            "catename": "스터디카페,스터디룸",
            "cate1name": "서비스,산업",
            "fullCateIds": "7|16|22931|23758"
        },
        "englishname": "Wing Study",
        "feedback": {
            "allphotocnt": 67,
            "blogrvwcnt": 6,
            "kascnt": 0,
            "comntcnt": 15,
            "scoresum": 74,
            "scorecnt": 15
        },
        "openHour": {
            "periodList": [
                {
                    "periodName": "영업기간",
                    "timeList": [
                        {
                            "timeName": "영업시간",
                            "timeSE": "09:00 ~ 23:00",
                            "dayOfWeek": "매일"
                        }
                    ]
                },
                {
                    "periodName": "공휴일",
                    "timeList": [
                        {
                            "timeName": "영업시간",
                            "timeSE": "09:00 ~ 23:00",
                            "dayOfWeek": "매일"
                        }
                    ]
                }
            ],
            "realtime": {
                "holiday": "N",
                "breaktime": "N",
                "open": "Y",
                "moreOpenOffInfoExists": "Y",
                "datetime": "20220710102427",
                "currentPeriod": {
                    "periodName": "영업기간",
                    "timeList": [
                        {
                            "timeName": "영업시간",
                            "timeSE": "09:00 ~ 23:00",
                            "dayOfWeek": "매일"
                        }
                    ]
                },
                "closedToday": "N"
            }
        },
        "operationInfo": {
            "appointment": "Y"
        },
        "facilityInfo": {
            "wifi": "Y",
            "parking": "N"
        },
        "tags": [
            "신촌스터디룸",
            "신촌스터디카페",
            "신촌역스터디룸",
            "이대스터디룸",
            "홍대스터디룸"
        ],
        "source": {
            "date": "2022.07.08."
        },
        "isStation": false
    },
    "reviewWriteBlocked": "NONE",
    "blogReview": {
        "placenamefull": "윙스터디 신촌스터디룸",
        "blogrvwcnt": 6,
        "list": [
            {
                "blogname": "서울에서 봄잠 코오오~",
                "blogurl": "http://blog.naver.com/sailor3",
                "contents": "신촌 스터디카페 윙스터디 신촌점 이번에 사용하면서 편의시설이랑 영업시간 등을 안내드리려고 찍어왔습니다 이 건물 지하1층에 위치해 있습니다. 내려가면 이렇게 널찍 깔끔하고 밝은 윙스터디 신촌점이 나와요. 저는 예약을 잡고 가서 인원과 시간을 예약하고 가서 예약자 이름 이야기 하면 방 번호를 이야기 해주십니다. 방은 이렇게 3줄로 되어 있는데요 번호가 적혀 있어서 알려주신 번호 이렇게 지도 보고 바로 찾아가기 쉬웠습니다. 최대 4인까지 이용이 가능한 방이에요 신촌 스터디카페 모임이나 스터디, 과외 등도 가능한 곳입니다. 가격도 착하고 거기다가 컴퓨터도 쓸 수 있고 와이파이도 있고 시원하고 격리된 공간을 사용할 수 있는 곳이라 카페보다는 더욱 프라이빗하게 사용이 가능해서 신촌 갈 일이 있어서 예약잡고 ",
                "outlink": "http://blog.naver.com/sailor3/222796652973",
                "date": "2022.07.01.",
                "reviewid": "29450192",
                "title": "신촌 스터디카페 윙스터디 신촌점 편의시설 영업시간",
                "photoList": [
                    {
                        "orgurl": "https://postfiles.pstatic.net/MjAyMjA3MDFfMTcg/MDAxNjU2NjczNDY5Mzk1.XLO79Oie_hnruCyilz4NGl0rZWPW9O0lQx9mDMBFXKAg.kd0jmLPLHArkUf6f-hdJp_oULhFNlsNdKjT4t-Mu7zgg.JPEG.sailor3/01.JPG?type=w966"
                    },
                    {
                        "orgurl": "https://postfiles.pstatic.net/MjAyMjA3MDFfOTYg/MDAxNjU2NjczNDY5NDY5.xNu5Vb3pPvp5g41tUfnWWVMLPZXN69dNgPkNgVQHPgMg.9JkdZTNLR92tjfIY6jeioWdPk2gTuROG4EJwORGD5wog.JPEG.sailor3/02.JPG?type=w966"
                    },
                    {
                        "orgurl": "https://postfiles.pstatic.net/MjAyMjA3MDFfNjYg/MDAxNjU2NjczNDY5NDY3.NkGAHRoxBbRzF2Hu7ZmOeTQ1IM81oF7HpoQAXKNVk30g.zKrmCPYh1E-c2kSSXgiuhAnkmshnQjpXpKACCJchy7Eg.JPEG.sailor3/03.JPG?type=w966"
                    },
                    {
                        "orgurl": "https://postfiles.pstatic.net/MjAyMjA3MDFfMTU1/MDAxNjU2NjczNDY5NDY1.yqv3VdqBzb853ZINVaK01IC9JtAAzTyMTuzwOB5Rw3cg.nV6L00zUZyoOlxt_o8IdYDHqA-wULdfx1r44KLysOH8g.JPEG.sailor3/04.JPG?type=w966"
                    },
                    {
                        "orgurl": "https://postfiles.pstatic.net/MjAyMjA3MDFfMTAy/MDAxNjU2NjczNDY5NTQx.gY2de9nxwPrIQf4KojYnBuqOWqGkJhrr1DHBBd785mog.uFFB5qNaybKbICOPsbe-wNEnMx1iuczyGwAybKKH4cUg.JPEG.sailor3/05.JPG?type=w966"
                    },
                    {
                        "orgurl": "https://postfiles.pstatic.net/MjAyMjA3MDFfMjg0/MDAxNjU2NjczNDY5NDU4.myMAwZFxCZTzWuA_TuhoWhBTWL5DrMdSfZKozR5gf3cg.31KKVgi93-xaXWN3gEtCQRkJljpxny7GxPTNqknnockg.JPEG.sailor3/06.JPG?type=w966"
                    },
                    {
                        "orgurl": "https://postfiles.pstatic.net/MjAyMjA3MDFfMjQx/MDAxNjU2NjczNDcwMzI2.Z65sL4ViVisinYa8X0KgJHItGVsQqPxozKvdRvVik2og.dEPfl4j4wGIfHJJ_LqXDeZFI3utWZzbyd4TVgdNcS8Ig.JPEG.sailor3/07.JPG?type=w966"
                    },
                    {
                        "orgurl": "https://postfiles.pstatic.net/MjAyMjA3MDFfMTI4/MDAxNjU2NjczNDcwNDQ5.FFoz2oc7HMvRD_uIunUg3TjcolJuNrAw5KPjw5yOrGIg.7-eVTHHyQDOhheDFvfauWTC2ykvD7ZcSak4a4ei58d4g.JPEG.sailor3/08.JPG?type=w966"
                    },
                    {
                        "orgurl": "https://postfiles.pstatic.net/MjAyMjA3MDFfMyAg/MDAxNjU2NjczNDcwNTE2.A4k45iRGs_G13DsiaXBE7X5Hp58dKwHmaeYR9Ow380Ag.2SF8Aj9iwJ0z7BUcUMplraXBV8oRGlG9BhTXsX2eRmgg.JPEG.sailor3/09.JPG?type=w966"
                    },
                    {
                        "orgurl": "https://postfiles.pstatic.net/MjAyMjA3MDFfMTY0/MDAxNjU2NjczNDcwNTc0.9L8BSUQsTBJ_-osTEJ8vmg13R9bHa6qZdj6i44yUrXMg.SdyJAfLu3sOgjaue5B4CUNQXRRZvrJg8rxg_1P82Nuwg.JPEG.sailor3/10.JPG?type=w966"
                    }
                ],
                "isMy": false
            },
        ]
    },
    "comment": {
        "placenamefull": "윙스터디 신촌스터디룸",
        "kamapComntcnt": 15,
        "scoresum": 74,
        "scorecnt": 15,
        "currentPage": 1,
        "pageList": [
            1,
            2,
            3
        ],
        "list": [
            {
                "commentid": "5757455",
                "contents": "가성비가 완전 좋아요. 추천합니다.",
                "point": 5,
                "username": "이세영",
                "profileStatus": "S",
                "photoCnt": 0,
                "likeCnt": 0,
                "kakaoMapUserId": "1fssjah",
                "ownerReply": {},
                "date": "2022.06.28.",
                "isMy": false,
                "isBlock": false,
                "isEditable": false,
                "isMyLike": false
            },
            {
                "commentid": "5751943",
                "contents": "가격이 저렴하고 조용해서 좋았어요 자주 이용할듯 해요.",
                "point": 5,
                "username": "박고순",
                "profileStatus": "S",
                "photoCnt": 0,
                "likeCnt": 0,
                "kakaoMapUserId": "1qah947",
                "ownerReply": {},
                "date": "2022.06.27.",
                "isMy": false,
                "isBlock": false,
                "isEditable": false,
                "isMyLike": false
            },
            {
                "commentid": "5734603",
                "contents": "가격도 저렴하고 쾌적한 환경에서 업무할 수 있었습니다 :)",
                "point": 5,
                "username": "김민지",
                "profile": "http://t1.daumcdn.net/local/kakaomapPhoto/profile/abe17e362d777ea3e2f4013486628c074776c868deb329a72818677f4034e859",
                "profileStatus": "S",
                "photoCnt": 0,
                "likeCnt": 0,
                "kakaoMapUserId": "10tunlv",
                "ownerReply": {},
                "date": "2022.06.24.",
                "isMy": false,
                "isBlock": false,
                "isEditable": false,
                "isMyLike": false
            },
            {
                "commentid": "5729210",
                "contents": "직원분이 친절하셔서 매번 이용할 때 기분좋게 이용합니다! 공부하기에도 분위기가 좋습니다!",
                "point": 5,
                "username": "김유정",
                "profileStatus": "S",
                "photoCnt": 0,
                "likeCnt": 0,
                "kakaoMapUserId": "1q3an3h",
                "ownerReply": {},
                "date": "2022.06.23.",
                "isMy": false,
                "isBlock": false,
                "isEditable": false,
                "isMyLike": false
            },
            {
                "commentid": "5723647",
                "contents": "컴퓨터도 쓸 수 있고 , 화장실도 깨끗한 편이고 외부에 있지않아서 좋아요 추천!",
                "point": 5,
                "username": "김진아",
                "profileStatus": "S",
                "photoCnt": 0,
                "likeCnt": 0,
                "kakaoMapUserId": "1ph9611",
                "ownerReply": {},
                "date": "2022.06.22.",
                "isMy": false,
                "isBlock": false,
                "isEditable": false,
                "isMyLike": false
            }
        ]
    },

    "placeOwnerInfos": {
        "status": "REGISTERED",
        "ownPlaceId": 123647,
        "loginUserRelation": "OTHER",
        "newsInfo": {
            "totalCount": 0,
            "newsInfoList": []
        }
    },
    "menuInfo": {
        "menucount": 3,
        "menuList": [
            {
                "price": "1,700",
                "recommend": false,
                "menu": "1시간 이용 요금"
            },
            {
                "recommend": false,
                "menu": "아메리카노, 카페라떼"
            },
            {
                "recommend": false,
                "menu": "PC & 모니터 사용"
            }
        ],
        "productyn": "Y",
        "menuboardphotocount": 0
    },
    "photo": {
        "photoList": [
            {
                "photoCount": 67,
                "categoryName": "all",
                "list": [
                    {
                        "photoid": "M",
                        "orgurl": "http://t1.kakaocdn.net/mystore/61F07A40BE6142D9BED6B4D418A925A8"
                    },
                    {
                        "photoid": "R2",
                        "orgurl": "http://t1.kakaocdn.net/mystore/208F626F2B074D44AD66B8E8F27986DC"
                    },
                    {
                        "photoid": "R3",
                        "orgurl": "http://t1.kakaocdn.net/mystore/CD04B9DC8B8440B08D42A52EF0580997"
                    },
                    {
                        "photoid": "R4",
                        "orgurl": "http://t1.kakaocdn.net/mystore/EAD1DED158E24151A144906A657C5874"
                    },
                    {
                        "photoid": "R5",
                        "orgurl": "http://t1.kakaocdn.net/mystore/B4C4BA8DB9CB4D269A5FD6ED1247D3B5"
                    }
                ]
            }
        ]
    }
}
```