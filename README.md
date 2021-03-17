import DB from './firebase/tuma';

const usuarios = {

    nombre: 'RAMON',
    Años: 20,
    nacimiento: 0

}


const referencia = DB.collection('usuarios');
const usuariosRef = referencia


// DB.collection('usuarios')
//     .add(usuarios)
//     .then(docRef => {
//         //     console.log(docRef)
//     }
//     )
//     .catch(e => console.log('error', e))

// forma para cambiar algo de la base


// usuariosRef
//     .doc('WMCfFDLUVatbX6rt71Pv')
//     .update({
//         nombre: 'RAMO',
//         Años: 20.5,
//         nacimiento: 0

//     })

// //es lo mismo con es set solo que este borrar todo lo demas osea que solo deja lo que pones ahi si te pregunta es la forma destrutiva

// usuariosRef
//     .doc('zNpUFtjAiKz4cBPtXHsK')
//     .set({
//         nombre: 'RAMON'
//     })


// usuariosRef
//     .doc('')
//     .delete()
//     .then(resp => console.log(resp))
//     .catch(e => console.log('error', e));

// usuariosRef
//     .onSnapshot(snap => {
//         documents(snap);
//     })


// usuariosRef
//     .onSnapshot(documents);
