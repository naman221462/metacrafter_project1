let nfts = [];
console.log("ID: ","l43qoekd98m")
function mintNFT(name, description, creator) {
    let nft = {
        name: name,
        description: description,
        creator: creator
    };
    nfts.push(nft);
}

function listNFTs() {
    for (let i = 0; i < nfts.length; i++) {
        console.log("Name: " + nfts[i].name);
        console.log("Description: " + nfts[i].description);
        console.log("Creator: " + nfts[i].creator);
    }
}

function getTotalSupply() {
    return nfts.length;
}

mintNFT("NFT 1", "This is the first NFT", "Alice");
mintNFT("NFT 2", "This is the second NFT", "Bob");

listNFTs();
console.log("Total NFTs minted: " + getTotalSupply());
