# Clone repo to your Virtual Machine.
# Install Python & Pip
      sudo apt update 
      sudo apt install -y python3 python3-pip python3-venv
# Create a virtual environment ( Optional but recommended)
   cd ~python-demoapp/src
   python3 -m venv venv               #run this inside backend directory
   source venv/bin/activate
# Install Node Js 
 Download and install nvm:
    curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash
in lieu of restarting the shell
    \. "$HOME/.nvm/nvm.sh"                                                   #Run all these cmd inside frontend folder
    Download and install Node.js:
nvm install 22
     Verify the Node.js version:
node -v # Should print "v22.17.0".
     nvm current # Should print "v22.17.0". 
Verify npm version:
     npm -v # Should print "10.9.2".

# Now we will use two env variables 
  1-> env = open api key
    Go to your backend folder 
      vi .env
        paste your api key

        
 2->  env = Url of backend for frontend 
      Go to your Frontend folder
         Vi .env
             

   
