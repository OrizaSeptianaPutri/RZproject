//1. lifecycle adalah serangkaian langkah inisialisasi(nilai untuk mendeklasikan variable/objek) sampai komponen nya berhasil di jalankan.
<template>
 
</template>
//2. lifecycle dibagi menjadi 4 tipe, yaitu create, mount, updating, dan destruction.
//CREATING memungkinkan kita untuk menjalankan kode sesaat sebelum dan sesudah componen mengupdate DOM. pada tipe ini 
//terdapat 2 lifecycle :
<script>	
export default{
    beforeCreate(){
        console.log('before create');
        //BEFORECREATE dijalankan pertama kali ketika data belum diinisiasi oleh Vue
    },
    created(){
        console.log('created');
        //
    },
    beforeMount(){
        console.log('before mount');
    },
    mounted(){
        console.log('mounted');
    },
    beforeUpdate(){
        console.log('before update');
    },
    updated(){
        console.log('updated');
    },
    beforeDestroy(){
        console.log('before destroy');
    },
    destroyed(){
        console.log('destroy');
    }
}
</script>


 