<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>X Faucet - Claim Free Crypto</title>
    <style>
        body { text-align: center; font-family: Arial, sans-serif; padding: 20px; }
        h1 { color: #333; }
        input, button { margin: 10px; padding: 10px; width: 80%; }
        #status { margin-top: 20px; }
    </style>
</head>
<body>
    <h1>Welcome to X Faucet!</h1>
    <p>Enter your wallet address to claim free crypto.</p>
    <form id="claimForm">
        <input type="text" id="wallet" placeholder="Enter wallet address" required>
        <button type="submit">Claim Now</button>
    </form>
    <p id="status"></p>

    <script>
        document.getElementById('claimForm').addEventListener('submit', function(event) {
            event.preventDefault();
            const walletAddress = document.getElementById('wallet').value;
            if (walletAddress) {
                document.getElementById('status').innerText = `Claiming crypto for wallet: ${walletAddress}`;
            } else {
                document.getElementById('status').innerText = 'Please enter a valid wallet address.';
            }
        });
    </script>
</body>
</html>
