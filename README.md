// Decompiled by library.dedaub.com
// 2022.12.22 07:19 UTC

// Data structures and variables inferred from the use of storage instructions
uint256 stor_0; // STORAGE[0x0]


function 0x1308(uint256 varg0) private { 
    if (varg0) {
        return ;
    } else {
        v0 = new uint256[](0x5709238);
        CALLDATACOPY(v0.data, msg.data.length, 0xae124700);
        v1 = v2 = 0;
        while (1 > ~0x5709238) {
            require(1 <= ~0x5709238, Panic(17));
            if (v1 >= 0x5709239) {
                break;
            }
            if (v1 >= 0x5709239) {
                return ;
            }
            v3 = _SafeSub(block.number, v1);
            require(v1 < v0.length, Panic(50));
            v0[v1 << 5] = keccak256(block.blockhash(v3));
            require(v1 != ~0, Panic(17));
            v1 += 1;
        }
    }
}

function 0x13b0(uint256 varg0, uint256 varg1, uint256 varg2, uint256 varg3, uint256 varg4, uint256 varg5) private { 
    v0 = 0x1a75(varg3, varg5, varg4);
    if (!v0) {
        v1 = v2 = 0;
    } else {
        if (!varg1) {
            v1 = v3 = 0x1abf(varg0, varg5, varg2, 0);
        } else {
            v1 = v4 = 0x1abf(varg0, varg5, 0, varg2);
        }
        goto 0x13ed0x13b0;
    }
    return v1;
}

function 0x13f7(uint256 varg0, uint256 varg1, uint256 varg2, uint256 varg3, uint256 varg4, uint256 varg5, uint256 varg6) private { 
    v0, v1 = 0x1b28(varg6);
    if (!v0) {
        MEM[MEM[64] + 32] = varg0 & ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff;
        MEM[MEM[64] + 34] = varg1 & ~0xffffffffffffffffffffffff;
        MEM[MEM[64] + 54] = varg6 << 96 & ~0xffffffffffffffffffffffff;
        v2 = v3 = MEM[64];
        MEM[v3] = 42;
        MEM[64] += 74;
    } else {
        MEM[MEM[64] + 32] = varg0 & ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff;
        MEM[MEM[64] + 34] = varg1 & ~0xffffffffffffffffffffffff;
        MEM[MEM[64] + 54] = v1 & ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff;
        v2 = v4 = MEM[64];
        MEM[v4] = 23;
        MEM[64] += 55;
    }
    v5 = v6, v5 = v7 = 0x1b67(v2, varg4, varg3, varg2, varg5);
    if (!varg3) {
    }
    v8 = 0x1edf(v5);
    return v8;
}

function 0x14dc(uint256 varg0, uint256 varg1) private { 
    v0, v1 = 0x1b28(MEM[32 + varg0]);
    if (!v0) {
        MEM[MEM[64] + 32] = MEM[varg1 + 32] << 248;
        MEM[MEM[64] + 33] = ~0xffffffffffffffffffffffff & MEM[varg1] << 96;
        MEM[MEM[64] + 53] = ~0xffffffffffffffffffffffff & MEM[varg1 + 64] << 96;
        MEM[MEM[64] + 73] = MEM[varg1 + 128];
        MEM[MEM[64] + 105] = ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff & MEM[varg1 + 96] << 240;
        MEM[MEM[64] + 107] = ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff & MEM[varg0 + 128] << 240;
        MEM[MEM[64] + 109] = ~0xffffffffffffffffffffffff & MEM[96 + varg0] << 96;
        MEM[MEM[64] + 129] = ~0xffffffffffffffffffffffff & MEM[32 + varg0] << 96;
        v2 = v3 = MEM[64];
        MEM[v3] = 117;
        MEM[64] += 149;
    } else {
        MEM[MEM[64] + 32] = MEM[varg1 + 32] << 248;
        MEM[MEM[64] + 33] = ~0xffffffffffffffffffffffff & MEM[varg1] << 96;
        MEM[MEM[64] + 53] = ~0xffffffffffffffffffffffff & MEM[varg1 + 64] << 96;
        MEM[MEM[64] + 73] = MEM[varg1 + 128];
        MEM[MEM[64] + 105] = ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff & MEM[varg1 + 96] << 240;
        MEM[MEM[64] + 107] = ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff & MEM[varg0 + 128] << 240;
        MEM[MEM[64] + 109] = ~0xffffffffffffffffffffffff & MEM[96 + varg0] << 96;
        MEM[MEM[64] + 129] = v1 & ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff;
        v2 = v4 = MEM[64];
        MEM[v4] = 98;
        MEM[64] += 130;
    }
    v5 = v6, v5 = v7 = 0x1b67(v2, MEM[64 + varg0], MEM[160 + varg0], 0, MEM[0 + varg0]);
    if (!MEM[160 + varg0]) {
    }
    v8 = 0x1edf(v5);
    return v8;
}

function 0x1683() private { 
    v0 = v1 = msg.sender == 0xfac983fce7ef3cee8ffb2ceb967e1b2362aada00;
    if (msg.sender != 0xfac983fce7ef3cee8ffb2ceb967e1b2362aada00) {
        v0 = v2 = msg.sender == 0x811fd1808e14f0b93f0514313965a5f142c5539;
    }
    if (!v0) {
        v0 = v3 = msg.sender == 0x681535922425a4264b3670d9430afc6dc4de103e;
        goto 0x13080x1683;
    }
    if (!v0) {
        v4 = new uint256[](0x5709238);
        CALLDATACOPY(v4.data, msg.data.length, 0xae124700);
        v5 = v6 = 0;
        while (1 > ~0x5709238) {
            require(1 <= ~0x5709238, Panic(17));
            if (v5 >= 0x5709239) {
                break;
            }
            if (v5 >= 0x5709239) {
                goto 0x4330x1683;
            }
            v7 = _SafeSub(block.number, v5);
            require(v5 < v4.length, Panic(50));
            v4[v5 << 5] = keccak256(block.blockhash(v7));
            require(v5 != ~0, Panic(17));
            v5 += 1;
        }
    }
    return ;
}

function 0x1a75(uint256 varg0, uint256 varg1, uint256 varg2) private { 
    if (varg0) {
        v0 = address(varg1);
        v1 = v2, v3 = varg2.transfer(v0, varg0).gas(msg.gas);
    } else {
        v1 = v4 = 1;
    }
    return v1;
}

function 0x1abf(uint256 varg0, uint256 varg1, uint256 varg2, uint256 varg3) private { 
    if (varg0 != 0) {
    }
    v0 = varg1.swap(varg3, varg2, varg0, 128, 0).gas(msg.gas);
    return v0;
}

function 0x1b28(uint256 varg0) private { 
    if (0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2 != address(varg0)) {
        return 0, 0;
    } else {
        return 1, 0;
    }
}

function 0x1b67(uint256 varg0, uint256 varg1, uint256 varg2, uint256 varg3, uint256 varg4) private { 
    if (varg2) {
        v0 = v1 = 0x1000276a4;
    } else {
        v0 = v2 = 0xfffd8963efd1fc6a506488495d951d5263988d25;
    }
    if (varg3 != 0) {
    }
    v3 = MEM[varg0];
    v4 = v5 = 0;
    while (v4 < v3) {
        MEM[v4 + MEM[64] + 196] = MEM[32 + (varg0 + v4)];
        v4 += 32;
    }
    v6, v7, v8 = varg4.swap(varg3, varg2, varg1, v0, 160, v3).gas(msg.gas);
    require(v6);
    return v8, v7;
}

function _SafeSub(uint256 varg0, uint256 varg1) private { 
    require(varg0 >= varg1, Panic(17));
    return varg0 - varg1;
}

function 0x1edf(uint256 varg0) private { 
    require(varg0 != 0x8000000000000000000000000000000000000000000000000000000000000000, Panic(17));
    return 0 - varg0;
}

function () public payable { 
    if (0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2 != msg.sender) {
        require(0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2.code.size);
        v0 = 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2.deposit().value(msg.value).gas(msg.gas);
        require(v0); // checks call status, propagates error data on error
    }
}

function 0x181266e2(uint256 varg0, uint256 varg1, uint256 varg2, uint256 varg3) public payable { 
    require(msg.data.length - 4 >= 128);
    require(varg0 == address(varg0));
    require(varg1 <= 0xffffffffffffffff);
    require(4 + varg1 + 31 < msg.data.length);
    require(varg1.length <= 0xffffffffffffffff);
    require(4 + varg1 + varg1.length + 32 <= msg.data.length);
    require(msg.data.length - 68 >= 64);
    0x1683();
    require(32 >= 32);
    require(varg2 == varg2 & ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffff);
    if (~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffff & varg2) {
        v0 = _SafeSub(block.number, 1);
        require(32 >= 32);
        require(varg2 == varg2 & ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffff);
        require(~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffff & varg2 == ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffff & keccak256(block.timestamp, block.blockhash(v0)), Error(0x4445460000000000000000000000000000000000000000000000000000000000));
    }
    v1 = new array[](varg1.length);
    v1[varg1.length] = 0;
    require((address(varg0)).code.size);
    v2 = address(varg0).call(0x3095c057, v1).gas(msg.gas);
    require(v2); // checks call status, propagates error data on error
    if (msg.value) {
        v3 = block.coinbase.call().value(msg.value).gas(2300 * !msg.value);
        require(v3); // checks call status, propagates error data on error
    }
    require(stor_0 > 0x56bc75e2d63100000, Error(0x4c4f570000000000000000000000000000000000000000000000000000000000));
    require(0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2.code.size);
    v4, v5 = 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2.balanceOf(this).gas(msg.gas);
    require(v4); // checks call status, propagates error data on error
    require(MEM[64] + RETURNDATASIZE() - MEM[64] >= 32);
    v6 = _SafeSub(v5, msg.value);
    require(v6 > varg3, Error(0x5046000000000000000000000000000000000000000000000000000000000000));
    v7 = _SafeSub(v5, msg.value);
    require(v7 > stor_0, Error(0x5053460000000000000000000000000000000000000000000000000000000000));
}

function delegate(address varg0) public payable { 
    require(msg.data.length - 4 >= 32);
    require(varg0 == varg0);
    0x342();
    v0 = varg0.delegatecall(MEM[(MEM[64]) len (msg.data.length - 36)], MEM[0 len 0]).gas(msg.gas);
    require(v0MEM[64], RETURNDATASIZE());
    return MEM[(MEM[64]) len (RETURNDATASIZE())];
}

function 0x7c04575b() public nonPayable { 
    0x1683();
    stor_0 = 1;
}

function 0x979bdc8e(uint256 varg0, uint256 varg1, uint256 varg2, uint256 varg3) public payable { 
    require(msg.data.length - 4 >= 128);
    require(varg0 == address(varg0));
    require(varg1 <= 0xffffffffffffffff);
    require(4 + varg1 + 31 < msg.data.length);
    require(varg1.length <= 0xffffffffffffffff);
    require(4 + varg1 + varg1.length + 32 <= msg.data.length);
    require(msg.data.length - 68 >= 64);
    0x1683();
    require(32 >= 32);
    require(varg2 == varg2 & ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffff);
    if (~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffff & varg2) {
        v0 = _SafeSub(block.number, 1);
        require(32 >= 32);
        require(varg2 == varg2 & ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffff);
        require(~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffff & varg2 == ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffff & keccak256(block.timestamp, block.blockhash(v0)), Error(0x4445460000000000000000000000000000000000000000000000000000000000));
    }
    require(0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2.code.size);
    v1, v2 = 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2.balanceOf(this).gas(msg.gas);
    require(v1); // checks call status, propagates error data on error
    require(MEM[64] + RETURNDATASIZE() - MEM[64] >= 32);
    MEM[MEM[64] + 68] = varg3;
    MEM[MEM[64] + 32] = 0xa9059cbb00000000000000000000000000000000000000000000000000000000 | 0xffffffffffffffffffffffffffffffffffffffffffffffffffffffff & address(varg0);
    v3 = v4 = 0;
    while (v3 < 68) {
        MEM[v3 + MEM[64]] = MEM[32 + (MEM[64] + v3)];
        v3 += 32;
    }
    if (v3 > 68) {
        MEM[MEM[64] + 68] = 0;
    }
    v5 = v6, v7, v8 = 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2.call(MEM[(MEM[64]) len 68], MEM[(MEM[64]) len 0]).gas(msg.gas);
    if (RETURNDATASIZE() == 0) {
        v9 = v10 = 96;
    } else {
        v9 = v11 = new bytes[](RETURNDATASIZE());
        RETURNDATACOPY(v11.data, 0, RETURNDATASIZE());
    }
    if (v6) {
        v5 = v12 = !MEM[v9];
        if (MEM[v9]) {
            require(v8 + MEM[v9] - v8 >= 32);
            v5 = MEM[v8];
            require(v5 == v5);
            goto 0x1921B0xd69;
        }
    }
    require(v5, Error('TransferHelper::safeTransfer: transfer failed'));
    v13 = new array[](varg1.length);
    v13[varg1.length] = 0;
    require((address(varg0)).code.size);
    v14 = address(varg0).call(0x3095c057, v13).gas(msg.gas);
    require(v14); // checks call status, propagates error data on error
    stor_0 = v2;
}

function destroy(uint256 varg0) public nonPayable { 
    require(msg.data.length - 4 >= 32);
    0x342();
    if (varg0) {
        require(0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2.code.size);
        v0 = 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2.withdraw(varg0).gas(msg.gas);
        require(v0); // checks call status, propagates error data on error
        v1 = new struct(1);
        v1.word0 = 0;
        v2 = v3 = 0;
        while (v2 < v1.word0) {
            MEM[v2 + (v1 + 32)] = MEM[32 + (v1 + v2)];
            v2 += 32;
        }
        if (v2 > v1.word0) {
            MEM[v1 + 32 + v1.word0] = 0;
        }
        v4, v5 = msg.sender.call(MEM[(MEM[64]) len (v1.word0 + (v1 + 32) - MEM[64])], MEM[(MEM[64]) len 0]).value(varg0).gas(msg.gas);
        if (RETURNDATASIZE() != 0) {
            v6 = new bytes[](RETURNDATASIZE());
            v5 = v6.data;
            RETURNDATACOPY(v5, 0, RETURNDATASIZE());
        }
        require(v4, Error(0x4445530000000000000000000000000000000000000000000000000000000000));
    }
    selfdestruct(msg.sender);
}

function uniswapV3SwapCallback(int256 varg0, int256 varg1, bytes varg2) public nonPayable { 
    require(msg.data.length - 4 >= 96);
    require(varg2 <= 0xffffffffffffffff);
    require(4 + varg2 + 31 < msg.data.length);
    require(varg2.length <= 0xffffffffffffffff);
    require(4 + varg2 + varg2.length + 32 <= msg.data.length);
    v0 = v1 = tx.origin == 0xb58555fcba6479fced7de1485eb054943a09af7b;
    if (tx.origin != 0xb58555fcba6479fced7de1485eb054943a09af7b) {
        v0 = v2 = tx.origin == 0xb7ab1de5b259a880c4bb5451bdbe6f80f3798538;
    }
    if (!v0) {
        v0 = v3 = tx.origin == 0x4f80b2cd1f550f81581c15f690bdd623f3824c86;
    }
    if (!v0) {
        v0 = v4 = tx.origin == 0x5b5001c4f80f33ec93b891062ed2e1d0acc05bb6;
    }
    if (!v0) {
        v0 = v5 = tx.origin == 0xa6ae57b1da8238cd149bc718c40578e4620b752c;
    }
    if (!v0) {
        v0 = v6 = tx.origin == 0x26ce7c1976c5eec83ea6ac22d83cb341b08850af;
    }
    if (!v0) {
        v0 = v7 = tx.origin == 0x52b86a86e4d764e8275391c436127e60340a0e6a;
    }
    if (!v0) {
        v0 = tx.origin == 0x41d3ab85aafed2ef9e644cb7d3bbca2fc4d8cac8;
    }
    require(v0);
    v8 = v9 = varg0 > 0;
    if (varg0 <= 0) {
        v8 = varg1 > 0;
    }
    require(v8, Error(0x4330000000000000000000000000000000000000000000000000000000000000));
    require(varg2.length > 22, Error(0x4339000000000000000000000000000000000000000000000000000000000000));
    MEM[64] = MEM[64] + 160;
    MEM[MEM[64]] = 0;
    MEM[MEM[64] + 32] = 0;
    MEM[MEM[64] + 64] = 0;
    MEM[MEM[64] + 96] = 0;
    MEM[MEM[64] + 128] = 0;
    v10 = v11 = 0;
    if (varg2.length > 42) {
        CALLDATACOPY(MEM[64], 132, 117);
        MEM[MEM[64]] = MEM[MEM[64] - 31];
        MEM[MEM[64] + 32] = address(MEM[MEM[64] - 11]);
        MEM[MEM[64] + 64] = address(MEM[MEM[64] + 9]);
        MEM[MEM[64] + 96] = MEM[MEM[64] + 41];
        MEM[MEM[64] + 128] = MEM[MEM[64] + 73];
        v12 = v13 = uint16(MEM[MEM[64] + 45]);
        v10 = v14 = MEM[MEM[64] + 65];
        if (varg2.length != 98) {
            v10 = v15 = MEM[MEM[64] + 85];
        }
    } else {
        CALLDATACOPY(MEM[64], 132, 42);
        v12 = v16 = uint16(MEM[MEM[64] - 30]);
        v10 = v17 = MEM[MEM[64] - 10];
        if (varg2.length != 23) {
            v10 = v18 = MEM[MEM[64] + 10];
        }
    }
    if (!address(v10)) {
        v10 = v19 = 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2;
    }
    if (address(v10) >= address(v10)) {
    }
    MEM[64] = MEM[64] + 128;
    MEM[MEM[64] + 160] = ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff;
    MEM[MEM[64] + 161] = 0x1f98431c8ad98523631ae4a59f267346ea31f984000000000000000000000000;
    MEM[MEM[64] + 181] = keccak256(address(v10), address(v10), 0xffffff & v12);
    MEM[MEM[64] + 213] = 0xe34f199b19b2b4f47f68442619d555527d244f78a3297ea89325f843f87b8b54;
    v20 = new array[](213 + (MEM[64] - v20));
    MEM[64] = MEM[64] + 245;
    v21 = v20.length;
    v22 = v20.data;
    if (varg0 <= 0) {
    }
    require(address(keccak256(v20)) == msg.sender, Error(0x3a29000000000000000000000000000000000000000000000000000000000000));
    if (varg2.length <= 42) {
        v23 = 0x1a75(v24, keccak256(v20), v10);
        require(v23, Error(0x4334000000000000000000000000000000000000000000000000000000000000));
    } else {
        if (!MEM[MEM[64]]) {
            v25 = 0x13f7(MEM[128 + MEM[64]], v10 << 96, keccak256(v20), address(MEM[64 + MEM[64]]) < address(v10), MEM[96 + MEM[64]], MEM[32 + MEM[64]], MEM[64 + MEM[64]]);
            require(v25 >= v24, Error(0x4333000000000000000000000000000000000000000000000000000000000000));
        } else {
            v26 = 0x13b0(keccak256(v20), address(MEM[64 + MEM[64]]) > address(v10), v24, MEM[96 + MEM[64]], MEM[64 + MEM[64]], MEM[32 + MEM[64]]);
            require(v26, Error(0x4332000000000000000000000000000000000000000000000000000000000000));
        }
        goto 0x12fcB0x33d;
    }
}

function 0x342() private { 
    v0 = v1 = msg.sender == 0xa6ae57b1da8238cd149bc718c40578e4620b752c;
    if (msg.sender != 0xa6ae57b1da8238cd149bc718c40578e4620b752c) {
        v0 = v2 = msg.sender == 0x26ce7c1976c5eec83ea6ac22d83cb341b08850af;
    }
    if (!v0) {
        v0 = v3 = msg.sender == 0xb58555fcba6479fced7de1485eb054943a09af7b;
    }
    if (!v0) {
        v0 = v4 = msg.sender == 0xb7ab1de5b259a880c4bb5451bdbe6f80f3798538;
    }
    if (!v0) {
        v0 = v5 = msg.sender == 0x4f80b2cd1f550f81581c15f690bdd623f3824c86;
    }
    if (!v0) {
        v0 = v6 = msg.sender == 0x5b5001c4f80f33ec93b891062ed2e1d0acc05bb6;
    }
    if (!v0) {
        v0 = v7 = msg.sender == 0x52b86a86e4d764e8275391c436127e60340a0e6a;
    }
    if (!v0) {
        v0 = v8 = msg.sender == 0x41d3ab85aafed2ef9e644cb7d3bbca2fc4d8cac8;
    }
    if (!v0) {
        v9 = new uint256[](0x5709238);
        CALLDATACOPY(v9.data, msg.data.length, 0xae124700);
        v10 = v11 = 0;
        while (1 > ~0x5709238) {
            require(1 <= ~0x5709238, Panic(17));
            if (v10 >= 0x5709239) {
                break;
            }
            if (v10 >= 0x5709239) {
                goto 0x4330x342;
            }
            v12 = _SafeSub(block.number, v10);
            require(v10 < v9.length, Panic(50));
            v9[v10 << 5] = keccak256(block.blockhash(v12));
            require(v10 != ~0, Panic(17));
            v10 += 1;
        }
    }
    return ;
}

// Note: The function selector is not present in the original solidity code.
// However, we display it for the sake of completeness.

function __function_selector__(bytes4 function_selector) public payable { 
    MEM[64] = 128;
    if (msg.data.length < 4) {
        if (!msg.data.length) {
            ();
        }
    } else if (0x181266e2 == function_selector >> 224) {
        0x181266e2();
    } else if (0x5c19a95c == function_selector >> 224) {
        delegate(address);
    } else if (0x7c04575b == function_selector >> 224) {
        0x7c04575b();
    } else if (0x979bdc8e == function_selector >> 224) {
        0x979bdc8e();
    } else if (0x9d118770 == function_selector >> 224) {
        destroy(uint256);
    } else if (0xfa461e33 == function_selector >> 224) {
        uniswapV3SwapCallback(int256,int256,bytes);
    }
    0x342();
    CALLDATACOPY(MEM[64], 0, 1);
    CALLDATACOPY(MEM[64], 1, 4);
    if (MEM[MEM[64]] & ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffff) {
        v0 = _SafeSub(block.number, 1);
        require(~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffff & MEM[MEM[64]] == ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffff & keccak256(block.timestamp, block.blockhash(v0)), Error(0x4445460000000000000000000000000000000000000000000000000000000000));
    }
    v1 = v2 = !(MEM[MEM[64]] & ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff);
    if (MEM[MEM[64]] & ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff) {
        v1 = v3 = MEM[MEM[64]] & ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff == 0x300000000000000000000000000000000000000000000000000000000000000;
    }
    if (!v1) {
        if (MEM[MEM[64]] & ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff > 0x500000000000000000000000000000000000000000000000000000000000000) {
            if (MEM[MEM[64]] & ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff != 0x600000000000000000000000000000000000000000000000000000000000000) {
                MEM[MEM[64]] = 0;
                MEM[MEM[64] + 32] = 0;
                MEM[MEM[64] + 64] = 0;
                MEM[MEM[64] + 96] = 0;
                MEM[MEM[64] + 128] = 0;
                MEM[MEM[64]] = 0;
                MEM[MEM[64] + 32] = 0;
                MEM[MEM[64] + 64] = 0;
                MEM[MEM[64] + 96] = 0;
                MEM[MEM[64] + 128] = 0;
                MEM[MEM[64] + 160] = 0;
                CALLDATACOPY(MEM[64], 5, 187);
                MEM[MEM[64] + 128] = MEM[MEM[64] + 155];
                MEM[MEM[64] + 96] = 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2;
                if (!(MEM[MEM[64]] >> 248 >> 1 & 0x1)) {
                    if (!((MEM[MEM[64]] >> 248 ^ 0x1) % 2)) {
                        v4 = 0x13f7(MEM[MEM[64] + 153] << 240, address(MEM[MEM[64] + 49]) << 96, address(MEM[MEM[64] + 9]), MEM[MEM[64]] >> 248 >> 2 & 0x1, MEM[MEM[64] + 81], address(MEM[MEM[64]] >> 248 >> 3), address(MEM[MEM[64] + 29]));
                        require(v4 >= MEM[MEM[64] + 113], Error(0x4533000000000000000000000000000000000000000000000000000000000000));
                    } else {
                        v5 = 0x13b0(address(MEM[MEM[64] + 9]), MEM[MEM[64]] >> 248 >> 2 & 0x1, MEM[MEM[64] + 113], MEM[MEM[64] + 81], address(MEM[MEM[64] + 29]), address(MEM[MEM[64]] >> 248 >> 3));
                        require(v5, Error(0x4532000000000000000000000000000000000000000000000000000000000000));
                    }
                    v6 = 0x13b0(0, MEM[MEM[64]] >> 248 >> 3, MEM[MEM[64] + 178] >> 224 << (MEM[MEM[64] + 177] >> 248 << 2), MEM[MEM[64] + 145], address(MEM[MEM[64] + 49]), address(MEM[MEM[64] + 9]));
                    0x1308(v6);
                } else {
                    v7 = 0x14dc(MEM[64], MEM[64]);
                    require(v7 >= MEM[MEM[64] + 178] >> 224 << (MEM[MEM[64] + 177] >> 248 << 2), Error(0x4531000000000000000000000000000000000000000000000000000000000000));
                }
                if (MEM[MEM[64]] & ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff == 0x800000000000000000000000000000000000000000000000000000000000000) {
                    v8 = block.coinbase.call().value(msg.value).gas(2300 * !msg.value);
                    require(v8); // checks call status, propagates error data on error
                }
            } else {
                MEM[MEM[64]] = 0;
                MEM[MEM[64] + 32] = 0;
                MEM[MEM[64] + 64] = 0;
                MEM[MEM[64] + 96] = 0;
                MEM[MEM[64] + 128] = 0;
                MEM[MEM[64]] = 0;
                MEM[MEM[64] + 32] = 0;
                MEM[MEM[64] + 64] = 0;
                MEM[MEM[64] + 96] = 0;
                MEM[MEM[64] + 128] = 0;
                MEM[MEM[64] + 160] = 0;
                CALLDATACOPY(MEM[64], 5, 187);
                MEM[MEM[64] + 128] = MEM[MEM[64] + 135];
                MEM[MEM[64] + 96] = address(MEM[MEM[64] + 155]);
                if (!(MEM[MEM[64]] >> 248 >> 1 & 0x1)) {
                    if (!((MEM[MEM[64]] >> 248 ^ 0x1) % 2)) {
                        v9 = 0x13f7(MEM[MEM[64] + 133] << 240, address(MEM[MEM[64] + 29]) << 96, address(MEM[MEM[64] + 9]), MEM[MEM[64]] >> 248 >> 2 & 0x1, MEM[MEM[64] + 62] >> 224 << (MEM[MEM[64] + 61] >> 248 << 2), address(MEM[MEM[64]] >> 248 >> 3), 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2);
                        require(v9 >= MEM[MEM[64] + 131], Error(0x5333000000000000000000000000000000000000000000000000000000000000));
                    } else {
                        v10 = 0x13b0(address(MEM[MEM[64] + 9]), MEM[MEM[64]] >> 248 >> 2 & 0x1, MEM[MEM[64] + 131], MEM[MEM[64] + 62] >> 224 << (MEM[MEM[64] + 61] >> 248 << 2), 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2, address(MEM[MEM[64]] >> 248 >> 3));
                        require(v10, Error(0x5332000000000000000000000000000000000000000000000000000000000000));
                    }
                    v11 = 0x13b0(0, MEM[MEM[64]] >> 248 >> 3, MEM[MEM[64] + 98], MEM[MEM[64] + 66], address(MEM[MEM[64] + 29]), address(MEM[MEM[64] + 9]));
                    0x1308(v11);
                } else {
                    v12 = 0x14dc(MEM[64], MEM[64]);
                    require(v12 >= MEM[MEM[64] + 98], Error(0x5331000000000000000000000000000000000000000000000000000000000000));
                }
                goto 0x1c9;
            }
        } else {
            CALLDATACOPY(MEM[64], 5, 78);
            if (MEM[MEM[64]] & ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff > 0x200000000000000000000000000000000000000000000000000000000000000) {
                CALLDATACOPY(MEM[64], 83, 3);
                v13 = 0x13f7(MEM[MEM[64] + 1], 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2000000000000000000000000, 0, MEM[MEM[64] + 77] & ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff, MEM[MEM[64] + 40], MEM[MEM[64] + 8], MEM[MEM[64] - 12]);
                0x1308(v13 >= MEM[MEM[64] + 73] >> 224 << (MEM[MEM[64] + 72] >> 248 << 2));
            } else {
                v14 = 0x13b0(0, !(MEM[MEM[64] + 77] & ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff), MEM[MEM[64] + 73] >> 224 << (MEM[MEM[64] + 72] >> 248 << 2), MEM[MEM[64] + 40], MEM[MEM[64] - 12], MEM[MEM[64] + 8]);
                0x1308(v14);
            }
            v15 = v16 = MEM[MEM[64]] & ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff == 0x200000000000000000000000000000000000000000000000000000000000000;
            if (MEM[MEM[64]] & ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff != 0x200000000000000000000000000000000000000000000000000000000000000) {
                v15 = v17 = MEM[MEM[64]] & ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff == 0x500000000000000000000000000000000000000000000000000000000000000;
            }
            if (v15) {
                v18 = block.coinbase.call().value(msg.value).gas(2300 * !msg.value);
                require(v18); // checks call status, propagates error data on error
            }
        }
        exit;
    } else {
        CALLDATACOPY(MEM[64], 5, 59);
        if (MEM[MEM[64]] & ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff > 0x200000000000000000000000000000000000000000000000000000000000000) {
            CALLDATACOPY(MEM[64], 64, 22);
            v19 = 0x13f7(MEM[MEM[64] + 20], MEM[MEM[64]], 0, MEM[MEM[64] + 57] & ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff, MEM[MEM[64] + 21] >> 224 << (MEM[MEM[64] + 20] >> 248 << 2), MEM[MEM[64] - 12], 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2);
            require(v19 >= MEM[MEM[64] + 25], Error(0x4631000000000000000000000000000000000000000000000000000000000000));
        } else {
            v20 = 0x13b0(0, MEM[MEM[64] + 57] & ~0xffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff, MEM[MEM[64] + 25], MEM[MEM[64] + 21] >> 224 << (MEM[MEM[64] + 20] >> 248 << 2), 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2, MEM[MEM[64] - 12]);
            0x1308(v20);
        }
    }
}
