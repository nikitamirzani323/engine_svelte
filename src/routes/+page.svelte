<script>
    import { goto } from '$app/navigation';
    import "../app.css";     
    
    let value = ['7000.000', '500.000', '600.000','1.250.000', '2.000.000', '1.750.000','5.000.000', '300.000', 
    '550.000','100.000', '500.000', '200.000','400.000', '110.000', '69.000','70.000', 
    '750.000', '95.000','70.000', '50.000', '100.000','88.000', '2.000.000', 
    '155.000','400.000', '120.000', '600.000','50.000', '80.000', '100.000','50.000', 
    '50.000', '30.100','200.000', 
    '95.000', '51.000', '50.000','580.000', '30.000', '150.000'];
    let value2 = ['10.000.000', '500.000', '600.000','1.300.0000', '25.000.0000', '10.700.000','5.000.000', 
    '900.000', '500.000','550.000', '45.000.000', '25.000.000','4.900.000', '1.100.000', 
    '1.700.000','6.500.000', '700.000', '15.000.000','200.000', '400.000', '4.800.000','900.000', '9.000.000', 
    '15.000.000','4.000.000', '7.500.000', '6.000.000','1.300.000', '700.000', '900.000','20.000.000', 
    '22.000.000', '4.100.000','14.000.000', '950.000', '790.000', '750.000','5.800.000', '3.000.000', '1.600.000' ,'12.000.000'];
    let currentIndex2 = Math.floor(Math.random() * 39) + 1;
    let currentInde2 = Math.floor(Math.random() * 40) + 1;

    let deposit_1 =  makeid(3)+'***' +  ' DEPOSIT '  +value[currentIndex2];
    let withdraw_1 =  makeid(3)+'***' +  ' WITHDRAW  '  +value2[currentIndex2]; 
    currentIndex2 = Math.floor(Math.random() * 39) + 1;
    currentInde2 = Math.floor(Math.random() * 40) + 1;
    let deposit_2 =  makeid(3)+'***' +  ' DEPOSIT '  +value[currentIndex2]; 
    let withdraw_2 =  makeid(3)+'***' +  ' WITHDRAW  '  +value2[currentIndex2]; 
    currentIndex2 = Math.floor(Math.random() * 39) + 1;
    currentInde2 = Math.floor(Math.random() * 40) + 1;
    let deposit_3 =  makeid(3)+'***' +  ' DEPOSIT '  +value[currentIndex2];  
    let withdraw_3 =  makeid(3)+'***' +  ' WITHDRAW  '  +value2[currentIndex2];  
    let deposit_4 =  ""; 
    let withdraw_4 =  ""; 
    let deposit_5 =  ""; 
    let withdraw_5 =  ""; 
    let deposit_6 =  ""; 
    let withdraw_6 =  ""; 
    let deposit_7 =  ""; 
    let withdraw_7 =  ""; 
    let deposit_8 =  ""; 
    let withdraw_8 =  ""; 
    let deposit_9 =  ""; 
    let withdraw_9 =  "";
    let deposit_10 =  ""; 
    let withdraw_10 =  "";  
    let field_username = "";
    let field_select = "";
    let table_td = "text-[#4efd09] text-center bg-black text-[10px] lg:text-[11-px]";
    let flat_first = true;
    let flat_second = false;
    let path_website = "https://mansione77.biz/register?ref=ysxfwbp";
    setInterval(() => {
            currentIndex2 = Math.floor((Math.random() *39) + 1);
            currentInde2 = Math.floor((Math.random() * 40) + 1);
            deposit_1 =  makeid(3)+'***' +  ' DEPOSIT '  +value[currentIndex2]; 
            withdraw_1 =  makeid(3)+'***' +  ' WITHDRAW  '  +value2[currentIndex2]; 
            currentIndex2 = Math.floor((Math.random() *39) + 1);
            currentInde2 = Math.floor((Math.random() * 40) + 1);
            deposit_2 =  makeid(3)+'***' +  ' DEPOSIT '  +value[currentIndex2]; 
            withdraw_2 =  makeid(3)+'***' +  ' WITHDRAW  '  +value2[currentIndex2];
            currentIndex2 = Math.floor((Math.random() *39) + 1);
            currentInde2 = Math.floor((Math.random() * 40) + 1);
            deposit_3 =  makeid(3)+'***' +  ' DEPOSIT '  +value[currentIndex2]; 
            withdraw_3 =  makeid(3)+'***' +  ' WITHDRAW  '  +value2[currentIndex2];
            currentIndex2 = Math.floor((Math.random() *39) + 1);
            currentInde2 = Math.floor((Math.random() * 40) + 1);
            deposit_4 =  makeid(3)+'***' +  ' DEPOSIT '  +value[currentIndex2]; 
            withdraw_4 =  makeid(3)+'***' +  ' WITHDRAW  '  +value2[currentIndex2];
            currentIndex2 = Math.floor((Math.random() *39) + 1);
            currentInde2 = Math.floor((Math.random() * 40) + 1);
            deposit_5 =  makeid(3)+'***' +  ' DEPOSIT '  +value[currentIndex2]; 
            withdraw_5 =  makeid(3)+'***' +  ' WITHDRAW  '  +value2[currentIndex2];
            currentIndex2 = Math.floor((Math.random() *39) + 1);
            currentInde2 = Math.floor((Math.random() * 40) + 1);
            deposit_6 =  makeid(3)+'***' +  ' DEPOSIT '  +value[currentIndex2]; 
            withdraw_6 =  makeid(3)+'***' +  ' WITHDRAW  '  +value2[currentIndex2];
            currentIndex2 = Math.floor((Math.random() *39) + 1);
            currentInde2 = Math.floor((Math.random() * 40) + 1);
            deposit_7 =  makeid(3)+'***' +  ' DEPOSIT '  +value[currentIndex2]; 
            withdraw_7 =  makeid(3)+'***' +  ' WITHDRAW  '  +value2[currentIndex2];
            currentIndex2 = Math.floor((Math.random() *39) + 1);
            currentInde2 = Math.floor((Math.random() * 40) + 1);
            deposit_8 =  makeid(3)+'***' +  ' DEPOSIT '  +value[currentIndex2]; 
            withdraw_8 =  makeid(3)+'***' +  ' WITHDRAW  '  +value2[currentIndex2]; 
            currentIndex2 = Math.floor((Math.random() *39) + 1);
            currentInde2 = Math.floor((Math.random() * 40) + 1);
            deposit_9 =  makeid(3)+'***' +  ' DEPOSIT '  +value[currentIndex2]; 
            withdraw_9 =  makeid(3)+'***' +  ' WITHDRAW  '  +value2[currentIndex2]; 
            currentIndex2 = Math.floor((Math.random() *39) + 1);
            currentInde2 = Math.floor((Math.random() * 40) + 1);
            deposit_10 =  makeid(3)+'***' +  ' DEPOSIT '  +value[currentIndex2]; 
            withdraw_10 =  makeid(3)+'***' +  ' WITHDRAW  '  +value2[currentIndex2];
        }, 5000)

    function makeid(length) {
        let result = '';
        const characters = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789';
        const charactersLength = characters.length;
        let counter = 0;
        while (counter <length) {
            result += characters.charAt(Math.floor(Math.random() * charactersLength));
            counter += 1;
        }
        return result;
    }
    const generate = () => {
        let msg = ""
        let flag = true
        if(field_username == ""){
            msg += "User ID harus diisi dengan benar\n"
            flag = false;
        }
        if(parseInt(field_username.length) < 4){
            msg += "User ID harus diisi dengan benar\n"
            flag = false;
        }
        if(field_select == ""){
            msg += "Pilih cheat\n";
            flag = false;
        }
        if(flag){
            showgenerate();
        }else{
            alert(msg)
        }
    };
    let game_value_1 = "0%";
    let game_value_2 = "0%";
    let game_value_3 = "0%";
    let game_value_4 = "0%";
    let game_value_5 = "0%";
    let game_value_6 = "0%";
    let game_value_7 = "0%";
    let game_value_8 = "0%";
    let game_value_9 = "0%";
    let game_value_10 = "0%";
    let game_value_11 = "0%";
    let game_value_12 = "0%";
    let game_value_text = "Loading...";
    let css_value_master = "text-center bg-black text-[10px] lg:text-[11px]"
    let css_value_1 = "text-red-400 ";
    let css_value_2 = "text-red-400 ";
    let css_value_3 = "text-red-400 ";
    let css_value_4 = "text-red-400 ";
    let css_value_5 = "text-red-400 ";
    let css_value_6 = "text-red-400 ";
    let css_value_7 = "text-red-400 ";
    let css_value_8 = "text-red-400 ";
    let css_value_9 = "text-red-400 ";
    let css_value_10 = "text-red-400 ";
    let css_value_11 = "text-red-400 ";
    let css_value_12 = "text-red-400 ";
    const showgenerate = () => {
        flat_first = false;
        flat_second = true;
        let i = 0;
        let i_2 = 0;
        let i_3 = 0;
        let i_4 = 0;
        let i_5 = 0;
        let i_6 = 0;
        let i_7 = 0;
        let i_8 = 0;
        let i_9 = 0;
        let i_10 = 0;
        let i_11 = 0;
        let i_12 = 0;
        setInterval(() => {
                if (i<30){
                    // document.getElementById("dd1").style.color ="red";
                    css_value_1 = "text-red-400 "
                     
                }else if(i<70){
                    // document.getElementById("dd1").style.color ="yellow";
                    css_value_1 = "text-yellow-400 "
                }else{
                    // document.getElementById("dd1").style.color ="green";
                    css_value_1 = "text-green-400 "
                }
                    game_value_1 = i+"%"; 
                if(i<100)
                {
                    i++;
                }else{
                    game_value_1 = "AKTIF"; 
                }
        },70)

        i_2=0;
        setInterval(() => {
                if (i_2<30){
                    // document.getElementById("dd1").style.color ="red";
                    css_value_2 = "text-red-400 "
                     
                }else if(i_2<70){
                    // document.getElementById("dd1").style.color ="yellow";
                    css_value_2 = "text-yellow-400 "
                }else{
                    // document.getElementById("dd1").style.color ="green";
                    css_value_2 = "text-green-400 "
                }
                    game_value_2 = i_2+"%"; 
                if(i_2<100){
                    i_2++;
                }else{
                    game_value_2 = "AKTIF"; 
                }
        },70)

        i_3=0;
        setInterval(() => {
                if (i_3<30){
                    // document.getElementById("dd1").style.color ="red";
                    css_value_3 = "text-red-400 "
                     
                }else if(i_3<70){
                    // document.getElementById("dd1").style.color ="yellow";
                    css_value_3 = "text-yellow-400 "
                }else{
                    // document.getElementById("dd1").style.color ="green";
                    css_value_3 = "text-green-400 "
                }
                    game_value_3 = i_3+"%"; 
                if(i_3<100){
                    i_3++;
                }else{
                    game_value_3 = "AKTIF"; 
                }
        },65)

        i_4 = 0;
        setInterval(() => {
                if (i_4<30){
                    css_value_4 = "text-red-400 "
                     
                }else if(i_4<70){
                    css_value_4 = "text-yellow-400 "
                }else{
                    css_value_4 = "text-green-400 "
                }
                    game_value_4 = i_4+"%"; 
                if(i_4<100){
                    i_4++;
                }else{
                    game_value_4 = "AKTIF"; 
                }
        },76)

        i_5 = 0;
        setInterval(() => {
                if (i_5<30){
                    css_value_5 = "text-red-400 "
                     
                }else if(i_5<70){
                    css_value_5 = "text-yellow-400 "
                }else{
                    css_value_5 = "text-green-400 "
                }
                    game_value_5 = i_5+"%"; 
                if(i_5<100){
                    i_5++;
                }else{
                    game_value_5 = "AKTIF"; 
                }
        },89)

        i_6 = 0;
        setInterval(() => {
                if (i_6<30){
                    css_value_6 = "text-red-400 "
                     
                }else if(i_6<70){
                    css_value_6 = "text-yellow-400 "
                }else{
                    css_value_6 = "text-green-400 "
                }
                    game_value_6 = i_6+"%"; 
                if(i_6<100){
                    i_6++;
                }else{
                    game_value_6 = "AKTIF"; 
                }
        },65)

        i_7 = 0;
        setInterval(() => {
                if (i_7<30){
                    css_value_7 = "text-red-400 "
                     
                }else if(i_7<70){
                    css_value_7 = "text-yellow-400 "
                }else{
                    css_value_7 = "text-green-400 "
                }
                    game_value_7 = i+"%"; 
                if(i_7<100){
                    i_7++;
                }else{
                    game_value_7 = "AKTIF"; 
                }
        },99)

        i_8 = 0;
        setInterval(() => {
                if (i_8<30){
                    css_value_8 = "text-red-400 "
                     
                }else if(i_8<70){
                    css_value_8 = "text-yellow-400 "
                }else{
                    css_value_8 = "text-green-400 "
                }
                    game_value_8 = i_8+"%"; 
                if(i_8<100)
                {
                    i_8++;
                }else{
                    game_value_8 = "AKTIF"; 
                }
        },51)

        i_9 = 0;
        setInterval(() => {
                if (i_9<30){
                    css_value_9 = "text-red-400 "
                     
                }else if(i_9<70){
                    css_value_9 = "text-yellow-400 "
                }else{
                    css_value_9 = "text-green-400 "
                }
                    game_value_9 = i_9+"%"; 
                if(i_9<100)
                {
                    i_9++;
                }else{
                    game_value_9 = "AKTIF"; 
                }
        },20)

        i_10 = 0;
        setInterval(() => {
                if (i_10<30){
                    css_value_10 = "text-red-400 "
                     
                }else if(i_10<70){
                    css_value_10 = "text-yellow-400 "
                }else{
                    css_value_10 = "text-green-400 "
                }
                    game_value_10 = i_10+"%"; 
                if(i_10<100){
                    i_10++;
                }else{
                    game_value_10 = "AKTIF"; 
                }
        },45)

        i_11 = 0;
        setInterval(() => {
                if (i_11<30){
                    // document.getElementById("dd1").style.color ="red";
                    css_value_11 = "text-red-400 "
                     
                }else if(i_11<70){
                    // document.getElementById("dd1").style.color ="yellow";
                    css_value_11 = "text-yellow-400 "
                }else{
                    // document.getElementById("dd1").style.color ="green";
                    css_value_11 = "text-green-400 "
                }
                    game_value_11 = i+"%"; 
                if(i_11<100){
                    i_11++;
                }else{
                    game_value_11 = "AKTIF"; 
                }
        },45)

        i_12 = 0;
        setInterval(() => {
                if (i_12<30){
                    // document.getElementById("dd1").style.color ="red";
                    css_value_12 = "text-red-400 "
                     
                }else if(i_12<70){
                    // document.getElementById("dd1").style.color ="yellow";
                    css_value_12 = "text-yellow-400 "
                }else{
                    // document.getElementById("dd1").style.color ="green";
                    css_value_12 = "text-green-400 "
                }
                    game_value_12 = i_12+"%"; 
                if(i_12<100){
                    i_12++;
                }else{
                    game_value_12 = "AKTIF"; 
                }
        },45)

        setTimeout(
                function(){
                    // document.getElementById("pros").style.color = "green"; 
                    // document.getElementById("pros").innerHTML = "MENUJU KE SITUS CHEAT.."; 
                    game_value_text = "MENUJU KE SITUS CHEAT..";
                },8000);
            
        setTimeout(
            function(){
                goto(path_website)
            },10000);
    }
</script>


<div class="navbar h-[90px] container mx-auto lg:px-1 xl:mt-0 max-w-screen-xl pb-2 ">
    <div class="flex-1">
        <a class="normal-case text-xl">
            <img
                style="width: 100px;" 
                src="https://i.ibb.co/Jr6S9Ns/2023-05-17-T11-00-08-955-Z-mansione77512.png" alt="">
        </a>
    </div>
    <div class="flex-none gap-2">
        <a href="{path_website}" class="btn btn-accent btn-sm">Daftar</a>
    </div>
</div>
<div class="text-black font-bold bg-[#ff7ac6] text-center text-lg mt-1">
    Aktifasi Minimal Saldo Rp 50.000
</div>
{#if flat_first}
<div class="container mx-auto lg:px-1 max-w-screen-xl pb-2 mt-5">
    <center class="text-white text-xs">
        ~ Masukkan User id (Pastikan Telah Terdaftar) : <br>
        ~ Harus Terdaftar disitus server Thailand<br>
        ~ Jika Belum Terdaftar Bisa Klik TOMBOL DAFTAR<br>
        Atau Tombol Daftar Diatas<br>
        <div class="col-sm-12 col-lg-2 mt-3 mb-3">
            <input
                bind:value={field_username}
                class="input input-bordered w-full max-w-xs text-center" type="text" placeholder="USER ID">
        </div>
        <div class="col-sm-12 col-lg-2 mt-3 mb-3">
            <select
                bind:value={field_select}
                style="text-align:center;" 
                class="select select-bordered w-full max-w-xs">
                <option value="">--Pilih Cheat--</option>
                <option value="1">Cheat Auto Scatter</option>
                <option value="2">Auto Sensational</option>
                <option value="3">Auto Wild</option>
            </select>
        </div>
        <button on:click={() => {
                generate();
            }}  type="button" class="btn btn-warning">AKTIVASI</button>
    </center>
</div>
{/if}
<div class="container mx-auto lg:px-1 xl:mt-0 max-w-screen-xl pb-2 " style="margin-top: 20px;">
    {#if flat_first}
        <table class="table ">
            <thead>
                <tr class="border-none">
                    <th class="text-[#4efd09] text-center bg-black">DEPOSIT TERAKHIR</th>
                    <th class="text-[#4efd09] text-center bg-black">WITHDRAW TERAKHIR</th>
                </tr>
            </thead>
            <tbody>
                <tr class="border-none">
                    <td class="text-[#4efd09] text-center bg-black text-[11px] lg:text-xs">{deposit_1}</td>
                    <td class="text-[#4efd09] text-center bg-black text-[11px] lg:text-xs">{withdraw_1}</td>
                </tr>
                <tr class="border-none">
                    <td class="{table_td}">{deposit_2}</td>
                    <td class="{table_td}">{withdraw_2}</td>
                </tr>
                <tr class="border-none">
                    <td class="{table_td}">{deposit_3}</td>
                    <td class="{table_td}">{withdraw_3}</td>
                </tr>
                <tr class="border-none">
                    <td class="{table_td}">{deposit_4}</td>
                    <td class="{table_td}">{withdraw_4}</td>
                </tr>
                <tr class="border-none">
                    <td class="{table_td}">{deposit_5}</td>
                    <td class="{table_td}">{withdraw_5}</td>
                </tr>
                <tr class="border-none">
                    <td class="{table_td}">{deposit_6}</td>
                    <td class="{table_td}">{withdraw_6}</td>
                </tr>
                <tr class="border-none">
                    <td class="{table_td}">{deposit_7}</td>
                    <td class="{table_td}">{withdraw_7}</td>
                </tr>
                <tr class="border-none">
                    <td class="{table_td}">{deposit_8}</td>
                    <td class="{table_td}">{withdraw_8}</td>
                </tr>
            </tbody>
        </table>
    {/if}
    {#if flat_second}
    <table class="table table-xs">
        <thead>
            <tr>
                <th colspan=2 class="text-white text-center bg-black">Username : {field_username}</th>
            </tr>
            <tr>
                <th colspan=2 class="text-white text-center bg-black">Sedang Mengaktifasi Cheat...</th>
            </tr>
            <tr class="border-none">
                <th class="text-[#4efd09] text-center bg-black">GAME</th>
                <th class="text-[#4efd09] text-center bg-black">AKTIFASI</th>
            </tr>
        </thead>
        <tbody>
            <tr class="border-none">
                <td class="{table_td}">NO LIMIT CITY</td>
                <td class="{css_value_1}{css_value_master}">{game_value_1}</td>
            </tr>
            <tr class="border-none">
                <td class="{table_td}">PRAGMATIC PLAY</td>
                <td class="{css_value_2}{css_value_master}">{game_value_2}</td>
            </tr>
            <tr class="border-none">
                <td class="{table_td}">PG SOFT</td>
                <td class="{css_value_3}{css_value_master}">{game_value_3}</td>
            </tr>
            <tr class="border-none">
                <td class="{table_td}">MICRO GAMING</td>
                <td class="{css_value_4}{css_value_master}">{game_value_4}</td>
            </tr>
            <tr class="border-none">
                <td class="{table_td}">HABANERO</td>
                <td class="{css_value_5}{css_value_master}">{game_value_5}</td>
            </tr>
            <tr class="border-none">
                <td class="{table_td}">SPADEGAMING</td>
                <td class="{css_value_6}{css_value_master}">{game_value_6}</td>
            </tr>
            <tr class="border-none">
                <td class="{table_td}">YGGDRASIL</td>
                <td class="{css_value_7}{css_value_master}">{game_value_7}</td>
            </tr>
            <tr class="border-none">
                <td class="{table_td}">JOKERGAMING</td>
                <td class="{css_value_8}{css_value_master}">{game_value_8}</td>
            </tr>
            <tr class="border-none">
                <td class="{table_td}">ADVANTPLAY</td>
                <td class="{css_value_9}{css_value_master}">{game_value_9}</td>
            </tr>
            <tr class="border-none">
                <td class="{table_td}">CQ9</td>
                <td class="{css_value_10}{css_value_master}">{game_value_10}</td>
            </tr>
            <tr class="border-none">
                <td class="{table_td}">NETENT</td>
                <td class="{css_value_11}{css_value_master}">{game_value_11}</td>
            </tr>
            <tr class="border-none">
                <td class="{table_td}">EVO CASINO</td>
                <td class="{css_value_12}{css_value_master}">{game_value_12}</td>
            </tr>
            <tr>
                <td colspan="2" class="text-center text-white">
                    {game_value_text}
                </td>
            </tr>
        </tbody>
    </table>
    {/if}
</div>

<footer class="footer footer-center p-2 bg-[#ff7ac6] text-black font-bold mt-5" style="background-color: #ff7ac6;">
    <div>
      <p>CHEATENGINE BY SERVER THAILAND</p>
    </div>
</footer>

