
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        /* Reset & Global Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
            background-color: #f8f8f8;
        }

        h1 {
            margin-bottom: 40px;
            font-size: 2.5em;
            color: #333;
        }

        /* Image Row Container */
        .image-container {
            width: 100%;
            max-width: 1200px;
        }

        /* Row Layout */
        .image-row {
            display: flex;
            justify-content: space-between;
            margin-bottom: 20px;
        }

        /* Image Styles */
        .image-row img {
            width: 48%;
            /* Allow for spacing */
            height: auto;
            /* Maintain aspect ratio */
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s ease;
        }

        /* Hover Effect */
        .image-row img:hover {
            transform: scale(1.05);
        }

        /* Reset & Global Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
            background-color: #f8f8f8;
        }

        h1 {
            margin-bottom: 40px;
            font-size: 2.5em;
            color: #333;
            text-align: center;
        }

        /* Image Container */
        .image-container {
            width: 100%;
            max-width: 1200px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
        }

        /* Image Styles */
        .image-container img {
            width: 100%;
            /* Fill grid columns */
            height: auto;
            /* Maintain aspect ratio */
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s ease;
        }

        /* Hover Effect */
        .image-container img:hover {
            transform: scale(1.05);
        }

        /* Mobile Responsive Adjustments */
        @media (max-width: 600px) {
            h1 {
                font-size: 2em;
            }

            .image-container {
                grid-template-columns: 1fr;
                /* Stack images vertically */
            }
        }
    </style>
</head>

<body>
    <div class="image-container">
        <!-- Image Rows -->
        <div class="image-row">
            <img src="https://res.cloudinary.com/dwkr6qrpf/image/upload/v1733562612/Food%20Menu/dyt8zetgjf19cw3q2kqg.png"
                alt="Image 1">
            <img src="https://res.cloudinary.com/dwkr6qrpf/image/upload/v1733564261/Food%20Menu/endtdd8pmqbgwmfmphxe.png"
                alt="Image 2">
        </div>

        <div class="image-row">
            <img src="https://res.cloudinary.com/dwkr6qrpf/image/upload/v1733564255/Food%20Menu/bagh4zgoxr5qgkpp3km8.png"
                alt="Image 3">
            <img src="https://res.cloudinary.com/dwkr6qrpf/image/upload/v1733564250/Food%20Menu/w8tvzl99cymip5yhtnas.png"
                alt="Image 4">
        </div>

        <div class="image-row">
            <img src="https://res.cloudinary.com/dwkr6qrpf/image/upload/v1733564254/Food%20Menu/aonsdusl5epdyzlmyqsh.png"
                alt="Image 5">
            <img src="https://res.cloudinary.com/dwkr6qrpf/image/upload/v1733564252/Food%20Menu/hxlrdu3lnr9fudhtdqlc.png"
                alt="Image 6">
        </div>

        <div class="image-row">
            <img src="https://res.cloudinary.com/dwkr6qrpf/image/upload/v1733565392/Food%20Menu/eaeeynftelp8fpb5elqc.png"
                alt="Image 7">
            <img src="https://res.cloudinary.com/dwkr6qrpf/image/upload/v1733565403/Food%20Menu/ozw1vdi6q1xcshccbsse.png"
                alt="Image 8">
        </div>

        <div class="image-row">
            <img src="https://res.cloudinary.com/dwkr6qrpf/image/upload/v1733565556/Food%20Menu/gbqsfup7dhk8yvtkf5un.png"
                alt="Image 9">
            <img src="https://res.cloudinary.com/dwkr6qrpf/image/upload/v1733565554/Food%20Menu/nztsgc2kv9pqylo8qfyt.png"
                alt="Image 10">
        </div>

        <div class="image-row">
            <img src="https://res.cloudinary.com/dwkr6qrpf/image/upload/v1733565646/Food%20Menu/udjdvqoaneyh7aiwb9zz.png"
                alt="Image 11">
            <img src="https://res.cloudinary.com/dwkr6qrpf/image/upload/v1733565647/Food%20Menu/pxsofujaqzs03fzmrhbh.png"
                alt="Image 12">
        </div>

        <div class="image-row">
            <img src="https://res.cloudinary.com/dwkr6qrpf/image/upload/v1733565767/Food%20Menu/bqddkxeqt4ydv33fg7ax.png"
                alt="Image 13">
            <img src="https://res.cloudinary.com/dwkr6qrpf/image/upload/v1733565766/Food%20Menu/e2dqx3bwlut5tziue39u.png"
                alt="Image 14">
        </div>

        <div class="image-row">
            <img src="https://res.cloudinary.com/dwkr6qrpf/image/upload/v1733565838/Food%20Menu/meupjp2feph9mb3ij2t8.png"
                alt="Image 15">
            <img src="https://res.cloudinary.com/dwkr6qrpf/image/upload/v1733565834/Food%20Menu/sj70ls01pe1iufqv5eek.png"
                alt="Image 16">
        </div>
    </div>

</body>

</html>
