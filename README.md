<!DOCTYPE html>
<html>
<head>
    <title>Rose</title>
    <style>
        /* Styles for the rose */
        .rose {
            width: 100px;
            height: 150px;
            position: relative;
        }

        /* Rose petals */
        .petal {
            width: 40px;
            height: 80px;
            background: #ff6699;
            border-radius: 50%;
            position: absolute;
            top: 20px;
        }

        .petal:nth-child(odd) {
            transform: rotate(45deg);
        }

        .petal:nth-child(even) {
            transform: rotate(-45deg);
        }

        .petal:nth-child(1) { left: 20px; }
        .petal:nth-child(2) { left: 45px; }
        .petal:nth-child(3) { left: 70px; }
        .petal:nth-child(4) { left: 95px; }

        /* Rose center */
        .center {
            width: 20px;
            height: 20px;
            background: #ff3366;
            border
