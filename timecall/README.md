# TimeCall
Не большой проект для себя (что-то на подобии Discord)

![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white)

<details>
<summary>Изображения</summary>
    
<img src="images/home.png" />
<img src="images/account.png" />
<img src="images/message.png" />
<img src="images/signin.png" />
<img src="images/signup.png" />
</details>

<details>
<summary>Пример кода React</summary>
    
```javascript
import React from 'react'
import $ from 'jquery'
import { Link } from 'react-router-dom'

import Avatar from '../../components/avatar/Avatar'

import { IoMdPersonAdd } from 'react-icons/io'
import { MdPersonRemoveAlt1 } from 'react-icons/md'

import { MdMessage } from 'react-icons/md'
import { ImBlocked } from 'react-icons/im'
import { MdReportProblem } from 'react-icons/md'
import { MdWallpaper } from 'react-icons/md'

import { TiInfoLargeOutline } from 'react-icons/ti'
import { RiGroupLine } from 'react-icons/ri'
import { BsFileEarmarkPost } from 'react-icons/bs'
import { TbFriends } from 'react-icons/tb'

import { TbListDetails } from 'react-icons/tb'
import { FaRegCalendarCheck } from 'react-icons/fa'
import { FaUserFriends } from 'react-icons/fa'

import './account.css'

export default function AccountPage()
{
    return (
        <section className="pageAccount">
            <div className="pageAccount-wrap">
                <div className="pageAccount-banner-mute">
                    <h1 className="pageAccount-banner-mute-h1">No Image</h1>
                    <div className="pageAccount-banner" style={{"background-image": "url(https://get.wallhere.com/photo/Kamado-Nezuko-Demon-Slayer-lantern-Kimetsu-no-Yaiba-1733063.jpg)"}}>
                        <div className="pageAccount-banner-wrap">
                            <div className="pageAccount-banner-wrap-elem">
                                <Avatar img="https://i.pinimg.com/736x/40/a9/4b/40a94b4c3473de7f425d95c5bbee3708.jpg" size="big" status="online" />
                                <h1 className="pageAccount-banner-name">
                                    <h2>
                                        LonelyNezuko
                                        <button className="btn-icon hint" data-hint="Удалить из друзей"><MdPersonRemoveAlt1 /></button>
                                        <button className="btn-icon hint" data-hint="Написать сообщение"><MdMessage /></button>
                                        <button className="btn-icon btn-icon-red"><ImBlocked /> <span style={{"margin-right": "0", "margin-left": "7px"}}>Заблокировать</span></button>
                                        <button className="btn-icon btn-icon-red"><MdReportProblem /> <span style={{"margin-right": "0", "margin-left": "7px"}}>Пожаловаться</span></button>
                                    </h2>
                                    <span>Не занят</span>
                                </h1>
                            </div>
                            <div className="pageAccount-banner-wrap-elem">
                                <button className="btn-icon">
                                    <span>Изменить фон</span>
                                    <MdWallpaper />
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
                <div className="pageAccount-body">
                    {/*<div className="pageAccount-body-nav">
                        <button className="btn btn-select">
                            <TiInfoLargeOutline />
                            Информация
                        </button>
                        <button className="btn">
                            <RiGroupLine />
                            Группы <span>285</span>
                        </button>
                        <button className="btn">
                            <BsFileEarmarkPost />
                            Посты <span>15</span>
                        </button>
                        <button className="btn">
                            <TbFriends />
                            Друзья <span>8592</span>
                        </button>
                    </div>*/}
                    <div className="pageAccount-body-wrap" id="pageAccountBodyInfo">
                        <div className="pageAccount-body-posts">
                            <div className="pageAccount-body-posts-regInfo">
                                <h1>Не много информации</h1>
                                <section>
                                    <button className="btn-icon btn-icon-transparent btn-non-cursor">
                                        <TbListDetails />
                                        <span style={{"margin-right": "0", "margin-left": "7px"}}>Идите нахуй, я сдох</span>
                                    </button>
                                    <button className="btn-icon btn-icon-transparent hint btn-non-cursor" data-hint="Дата регистрации">
                                        <FaRegCalendarCheck />
                                        <span style={{"margin-right": "0", "margin-left": "7px"}}>26.11.2022</span>
                                    </button>
                                    <button className="btn-icon btn-icon-transparent hint btn-non-cursor" data-hint="Подписчики">
                                        <FaUserFriends />
                                        <span style={{"margin-right": "0", "margin-left": "7px"}}>157.285</span>
                                    </button>
                                </section>
                            </div>
                        </div>
                        <div className="pageAccount-body-subs">
                            <div className="pageAccount-body-info-subs">
                                <a className="pageAccount-body-info-subs-title" href="/account#friends">
                                    Друзья
                                    <span>8.592</span>
                                </a>
                                <div className="pageAccount-body-info-subs-wrap">
                                    {/*<a href="/user?id=23" className="avatar avatar-medium avatar-status avatar-online">
                                        <div className="avatar-wrap">
                                            <img src="https://i.pinimg.com/736x/40/a9/4b/40a94b4c3473de7f425d95c5bbee3708.jpg" />
                                        </div>
                                        <h6>LonelyNezuko</h6>
                                    </a>
                                    <a href="/user?id=23" className="avatar avatar-medium avatar-status avatar-online">
                                        <div className="avatar-wrap">
                                            <img src="https://i.pinimg.com/736x/40/a9/4b/40a94b4c3473de7f425d95c5bbee3708.jpg" />
                                        </div>
                                        <h6>LonelyNezuko</h6>
                                    </a>*/}
                                    <h3>Пока еще нет друзей</h3>
                                </div>
                            </div>
                            <div className="pageAccount-body-info-subs">
                                <a className="pageAccount-body-info-subs-title" href="/account#friends">
                                    Группы
                                    <span>285</span>
                                </a>
                                <div className="pageAccount-body-info-subs-wrap">
                                    <a href="/user?id=23">
                                        <Avatar img="https://pixelbox.ru/wp-content/uploads/2021/03/anime-avatar-discord-46.jpg" size="medium" name="TimeCall" />
                                    </a>
                                    <a href="/user?id=23">
                                        <Avatar img="https://pixelbox.ru/wp-content/uploads/2021/06/ava-steam-anime-tyan-94.jpg" size="medium" name="New Channel" />
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    )
}
```
</details>

<details>
<summary>Пример кода CSS</summary>
    
```css
.pageAccount {
    width: 100%;
    height: 100%;

    overflow: hidden;
    border-radius: 8px;
}
.pageAccount-wrap {
    height: 100%;
    overflow: auto;
}
.pageAccount-wrap::-webkit-scrollbar {
    display: none;
}

.pageAccount .pageAccount-banner {
    width: 100%;
    height: 100%;

    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;

    background-position-y: 0%;
    background-position-x: 0%;

    position: absolute;

    top: 0;
    left: 0;

    border-radius: 8px 8px 0 0;
    z-index: 2;
}
.pageAccount .pageAccount-banner-mute {
    position: relative;

    width: 100%;
    height: 450px;

    background-color: #bdbdbd;
    border-radius: 8px 8px 0 0;
}
.pageAccount .pageAccount-banner-mute .pageAccount-banner-mute-h1 {
    position: absolute;

    top: 50%;
    left: 50%;

    transform: translate(-50%, -50%);

    font-size: 30px;
    font-weight: 700;
    text-transform: uppercase;
    opacity: .2;
}
.pageAccount .pageAccount-banner .pageAccount-banner-wrap {
    position: absolute;

    bottom: 0;
    left: 35px;

    /* transform: translateY(30%); */

    display: flex;
    align-items: flex-end;
    justify-content: space-between;

    width: calc(100% - 70px);
    padding-bottom: 25px;
}
.pageAccount .pageAccount-banner .pageAccount-banner-wrap .pageAccount-banner-wrap-elem {
    display: flex;
    align-items: flex-end;

    color: white;
}
.pageAccount .pageAccount-banner .pageAccount-banner-wrap .pageAccount-banner-wrap-elem .avatar {
    transform: translateY(20px);
}
.pageAccount .pageAccount-banner .pageAccount-banner-wrap .pageAccount-banner-wrap-elem .btn-icon {
    color: white;
}
.pageAccount .pageAccount-banner .pageAccount-banner-wrap .pageAccount-banner-name {
    margin-left: 20px;
}
.pageAccount .pageAccount-banner .pageAccount-banner-wrap .pageAccount-banner-name h2 {
    font-size: 25px;
    font-weight: 700;
    line-height: 25px;

    display: flex;
    align-items: center;
}
.pageAccount .pageAccount-banner .pageAccount-banner-wrap .pageAccount-banner-name h2 button:first-child {
    margin-left: 10px;
}
.pageAccount .pageAccount-banner .pageAccount-banner-wrap .pageAccount-banner-name h2 button {
    margin-left: 3px;
    color: white;
}
.pageAccount .pageAccount-banner .pageAccount-banner-wrap .pageAccount-banner-name span {
    font-size: 12px;
    opacity: .8;
}


.pageAccount .pageAccount-body {
    background: linear-gradient(90deg, #efefef, #b9deed);
    padding: 25px;

    border-radius: 0 0 8px 8px;
}

.pageAccount .pageAccount-body .pageAccount-body-nav {
    display: flex;
    align-items: center;

    border-bottom: 2px solid #9bd0e5;
    padding-bottom: 15px;
}
.pageAccount .pageAccount-body .pageAccount-body-nav .btn:not(:hover):not(.btn-select) {
    background: none;
    color: black;

    opacity: .6;
}
.pageAccount .pageAccount-body .pageAccount-body-nav .btn svg {
    margin-left: 0;
    margin-right: 5px;
}
.pageAccount .pageAccount-body .pageAccount-body-nav .btn + .btn {
    margin-left: 10px;
}
.pageAccount .pageAccount-body .pageAccount-body-nav .btn span {
    margin-left: 10px;

    background-color: black;
    color: white;
    border-radius: 4px;

    padding: 1px 6px;
    opacity: .2;
}
.pageAccount .pageAccount-body .pageAccount-body-nav .btn:hover span,
.pageAccount .pageAccount-body .pageAccount-body-nav .btn-select span {
    opacity: .6;
    background-color: white;
    color: black;
}


.pageAccount .pageAccount-body .pageAccount-body-wrap {
    margin-top: 15px;

    display: flex;
    align-items: flex-start;
    justify-content: space-between;
}
.pageAccount .pageAccount-body .pageAccount-body-info-flex {
    display: flex;
    justify-content: space-between;
}
.pageAccount .pageAccount-body .pageAccount-body-info-flex + .pageAccount-body-info-flex {
    margin-top: 15px;
}

.pageAccount .pageAccount-body .pageAccount-body-info-subs {
    width: calc(405px - 30px);
    padding: 15px;

    background: linear-gradient(90deg, #b9deed, #efefef);
    border-radius: 8px;
}
.pageAccount .pageAccount-body .pageAccount-body-info-subs + .pageAccount-body-info-subs {
    margin-top: 15px;
}
.pageAccount .pageAccount-body .pageAccount-body-info-subs .pageAccount-body-info-subs-title {
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.pageAccount .pageAccount-body .pageAccount-body-info-subs .pageAccount-body-info-subs-title span {
    font-size: 12px;
    opacity: .7;
}
.pageAccount .pageAccount-body .pageAccount-body-info-subs .pageAccount-body-info-subs-wrap {
    margin-top: 15px;

    display: flex;
    flex-wrap: wrap;
}
.pageAccount .pageAccount-body .pageAccount-body-info-subs .pageAccount-body-info-subs-wrap .avatar {
    margin-right: 15px;
    margin-bottom: 30px;
}
.pageAccount .pageAccount-body .pageAccount-body-info-subs .pageAccount-body-info-subs-wrap h3 {
    text-align: center;
    font-size: 12px;
    opacity: .6;

    width: 100%;
    padding: 30px 0;
}


.pageAccount .pageAccount-body .pageAccount-body-posts {
    width: 100%;
    margin-right: 20px;
}

.pageAccount .pageAccount-body .pageAccount-body-posts .pageAccount-body-posts-regInfo {
    width: 100%;

    background: linear-gradient(90deg, #b9deed, #efefef);
    border-radius: 8px;
}
.pageAccount .pageAccount-body .pageAccount-body-posts .pageAccount-body-posts-regInfo h1 {
    padding: 15px;
    border-bottom: 2px solid #9dc6d7;
}
.pageAccount .pageAccount-body .pageAccount-body-posts .pageAccount-body-posts-regInfo section {
    padding: 7px;
}
.pageAccount .pageAccount-body .pageAccount-body-posts .pageAccount-body-posts-regInfo .btn-icon span {
    opacity: .7;
}
```
</details>