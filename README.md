import React from 'react';
import Image from 'next/image';
import img from '../public/theme.png'

const HTML_Tem = () => {
    return (
        <>
            <div className="card justify-center w-full mt-5">
                <h1 className="text-3xl text-pink-700 underline font-Ubuntu mt-10 ml-16">HTML Templates</h1>
                <div className="wrap flex flex-wrap justify-center md:m-10 m-1">
                    <div className="card_hero shadow-2xl w-[400px] rounded-2xl m-10 cursor-pointer">
                        <Image src={img} width={400} height={225} />
                        <h1 className="m-5 text-lg font-Poppins text-left">
                            This is Title
                        </h1>
                        <p className="m-5">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Culpa, suscipit!</p>
                        <div className="btn m-10">
                            <a className="bg-blue-700 px-5 py-3 text-white md:text-xl text-sm rounded-xl hover:bg-blue-600">
                                Read Now
                            </a>
                        </div>
                    </div>
                    <div className="card_hero shadow-2xl w-[400px] rounded-2xl m-10 cursor-pointer">
                        <Image src={img} width={400} height={225} />
                        <h1 className="m-5 text-lg font-Poppins text-left">
                            This is Title
                        </h1>
                        <p className="m-5">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Culpa, suscipit!</p>
                        <div className="btn m-10">
                            <a className="bg-blue-700 px-5 py-3 text-white md:text-xl text-sm rounded-xl hover:bg-blue-600">
                                Read Now
                            </a>
                        </div>
                    </div>
                    <div className="card_hero shadow-2xl w-[400px] rounded-2xl m-10 cursor-pointer">
                        <Image src={img} width={400} height={225} />
                        <h1 className="m-5 text-lg font-Poppins text-left">
                            This is Title
                        </h1>
                        <p className="m-5">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Culpa, suscipit!</p>
                        <div className="btn m-10">
                            <a className="bg-blue-700 px-5 py-3 text-white md:text-xl text-sm rounded-xl hover:bg-blue-600">
                                Read Now
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </>
    )
}

export default HTML_Tem
